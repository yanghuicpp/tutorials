//***********************************************************************
// 
//		- "Talk to me like I'm a 3 year old!" Programming Lessons -		 
//                                                                       
//		$Author:	DigiBen	digiben@gametutorials.com			
//				
//		$Program:	Octree3	
//						 
//		$Description:	A working octree with a .3ds file format scene						
//	
//***********************************************************************

Files:  	Main.cpp (The Source File containing the main program code)
		Init.cpp (The Source File containing the Win32 and OpenGL initialization code)
		Camera.cpp (The Source File containing the camera class implementation)
		Frustum.cpp (The Source File containing the frustum implementation)
		3ds.cpp (The Source File containing the 3DS loader code)
		Octree.cpp (The Source File containing the octree implementation)
		Octree.h (The Header File containing "octree" definitions)
		3ds.h (The Header File containing the 3DS loader definitions)
		Frustum.h (The Header File containing the "frustum" definitions
		Camera.h (The Header File containing the camera class definition)
		main.h (The Header File containing definitions for the main program)
		Octree3.vcxproj  (The VC++ Project File holding the project info)
		Octree3.sln  (The Solution File holding the solution info)
		Park.3DS (The 3DS map file) 

Libraries:	opengl32.lib (The OpenGL Interface Library needed to compile the program)
		glu32.lib (The OpenGL Utility Library needed to compile the program)

Instructions:	If you have Microsoft Visual Studio 2005 just click on the
		<Program Name>.vcxproj file.  This will open up visual c++.  You will most
		likely see the code for <Program Name>.cpp.  If you don't, press CRTL+ALT+L
		This will open the "Solution Explorer".  There you should find two folders named
		"Source Files" and "Header Files".  Double click on the "source" folder and you
		should see your source file(s) with a .cpp extension after it.  Double click on the
		file and it will open up in your main window.  Hit Control-F5 to run the program.
		You will probably see a prompt to compile/build the project.  Click OK and
		the Win32 program should pop up. :)

EULA:  		Your use of this tutorial constitutes your agreement to GameTutorials' Terms of Use
		found at:  http://www.gametutorials.com/TermsOfUse.htm

www.GameTutorials.com
�2000-2006 GameTutorials