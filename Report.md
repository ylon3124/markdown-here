SID: 500179312

unikey: ylon3124

```Answer1
local variables：In the function, in the method of the class \
and the variable is not modified by self), this is a local \
variable, which is valid in this area and cannot be called in other places
instance variables: 
In the class method, and modified by self.

```Answer2
For instance method,the first parameter needs to be self, which represents a specific \
instance itself,for example: def get_first_name(self) is an instance \
method of class dorrigo_contact.Function does not need to mention self，、
and instance methods only apply to instance objects，Instance methods are \
meaningful inside the class, but functions can be called at will

```Answer3
If you use shallow copy, the elements in the original list message \
are changed, and the elements in the new list copy_message after the \
copy will also change, but if you use deep copy, the elements in \
copy_message will not change

```Answer4

| Class |  Instance Variable | Datatype  | Mutable |
| ------------- |:-------------:| :-----:| :-----:|
| mobile | first_name         | string 		| No    |
| mobile | phone_number       | list     	|   Yes |
| mobile | last_name          | string    |   No |
| mobile | is_phone_on        | bool    	|   Yes |
| mobile | get_battery_life   | int     	|   Yes |
| mobile | is_connected_network| bool     |   Yes |
| mobile | get_signal_strength | int     |   Yes |
| mobile | contact             | list     |   Yes |
| contact| fname               | string   |   No |
| contact| lname               | string   |   No |
| contact| pnumber             | list     |   Yes |
| contact| message             | list     |   Yes |
