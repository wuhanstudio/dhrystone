from building import *
import rtconfig

# get current directory
cwd     = GetCurrentDir()
# The set of source files associated with this SConscript file.
src     = Glob('*.c')

path    = [cwd + '/']

LOCAL_CCFLAGS = ''

group = DefineGroup('dhrystone', src, depend = ['PKG_USING_DHRYSTONE'], CPPPATH = path, LOCAL_CCFLAGS = LOCAL_CCFLAGS)

Return('group')
