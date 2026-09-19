<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWtt7De)"><path fill="url(#i7gPVOe)" class="z3krmcchz"/></g><g filter="url(#ibmIWQc)"><path fill="url(#iv6m9ad)" class="pa9dn_a9d"/></g><g filter="url(#i2WLrve)"><path fill="url(#iqNq1JR)" class="f0xgqdvvh"/><path fill="url(#im5YCpE)" class="f0xgqdvvh"/></g><g filter="url(#i1xC6Wd)"><path class="j_ran_v0u"/><path fill="url(#iDGsSkc)" class="ob5n74bcd"/><path fill="url(#iXGyCJc)" class="ob5n74bcd"/></g><g filter="url(#ie9MnCe)"><path fill="url(#idEY5yK)" class="xxsp33bgf"/><path fill="url(#ilt3szd)" class="xxsp33bgf"/><path fill="url(#if5R4kd)" class="xxsp33bgf"/><path fill="url(#iG1QFmb)" class="xxsp33bgf"/><path fill="url(#iOUYtid)" class="xxsp33bgf"/></g><path fill="url(#iTiPVMC)" class="xxsp33bgf"/><path fill="url(#ipnt3ab)" class="xxsp33bgf"/><path fill="url(#iq3k5nI)" class="xxsp33bgf"/><path fill="url(#iJRkggc)" class="xxsp33bgf"/><path fill="url(#i9NIVMW)" class="xxsp33bgf"/><path class="e6e5nabez"/><g filter="url(#iRpOSKd)"><path class="sdrp4rbiu"/></g><g filter="url(#iWOpVpd)"><path stroke="url(#i97Jtuc)" class="a9ok7vmop"/></g><g filter="url(#imj3gFb)"><path class="dtnh3t-ez"/></g><g filter="url(#iahMoOe)"><path stroke="url(#iss1cCd)" class="ox0lmrafs"/></g><g filter="url(#iGA6ILb)"><path class="nwawifxej"/><path fill="url(#iU3JUOd)" class="zb1lfmbev"/><path fill="url(#iZR1OIc)" class="zb1lfmbev"/><path fill="url(#iPd7gNb)" class="zb1lfmbev"/><path fill="url(#iZslZFD)" class="zb1lfmbev"/><path fill="url(#ioLmPnb)" class="zb1lfmbev"/></g><g filter="url(#iZ0ah8Q)"><path stroke="url(#iqH9GFb)" class="n5dtu37fp"/></g><g filter="url(#igWWope)"><path class="dpk1kv4yi"/></g><g filter="url(#iTB6Xhb)"><path class="fxde6r0oe"/><path fill="url(#iFEwzDb)" class="r85z0nboo"/><path fill="url(#iVPYmKc)" class="r85z0nboo"/><path fill="url(#iEl270b)" class="r85z0nboo"/><path fill="url(#iS4rHSl)" class="r85z0nboo"/></g><path fill="url(#idUfjDZ)" class="r85z0nboo"/><path class="jeuk3sh0v"/><path fill="url(#i0K5k5F)" class="j8ttpmb5k"/><path class="kzjv8db-k"/><g filter="url(#iK271Ed)"><path class="uv5y5wpjp"/><path fill="url(#iSKW7YZ)" class="vmna15bfy"/></g><g filter="url(#iappXOb)"><path fill="url(#i7SLEQd)" class="g96swhvgt"/></g><path class="klmhmr5xc"/><path fill="url(#i7FVJ5o)" class="iuv15ibzp"/><path class="g4-1rtdto"/><g filter="url(#iXokObc)"><path fill="url(#iZpYYnd)" class="wcydw6b9p"/></g><g filter="url(#iF1RMEb)"><ellipse transform="rotate(-27.914 11.039 16.923)" class="h_qkfoevi"/><ellipse fill="url(#ilDBlUd)" transform="rotate(-27.914 11.039 16.923)" class="grzb5abtp"/></g><g filter="url(#i8H5Yqb)"><path fill="url(#iDjsaPS)" class="ofusybc7o"/><path fill="url(#ik8ZS5c)" class="ofusybc7o"/></g><g filter="url(#iIlYtwe)"><path stroke="url(#iRcHnUc)" class="k05bo9wuy"/></g><g filter="url(#i2XDW3d)"><path class="ikymlcpqj"/></g><g filter="url(#iS4yP3c)"><path stroke="url(#iUq2Ppe)" class="i03znbcpp"/></g><g filter="url(#i6R1Hhf)"><path stroke="url(#ivoiTme)" class="mnsoe0bfo"/></g><g filter="url(#i00T1Ic)"><path stroke="url(#itk3cih)" class="wgy5ihboo"/></g><defs><radialGradient id="i7gPVOe" cx="0" cy="0" r="1" gradientTransform="matrix(3.41626 0 0 5.97849 2.99 17.71)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="im5YCpE" cx="0" cy="0" r="1" gradientTransform="matrix(1.60937 -1.17187 1.33754 1.8369 26.484 17.195)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iDGsSkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -3.21875 1.88395 1.02428 25.672 19.46)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iXGyCJc" cx="0" cy="0" r="1" gradientTransform="matrix(.55251 .5469 -.70503 .71226 25.76 17.71)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="idEY5yK" cx="0" cy="0" r="1" gradientTransform="matrix(-15.25009 7.91165 -8.96041 -17.27163 22.938 17.021)" gradientUnits="userSpaceOnUse"><stop class="am3a9544w"/><stop offset=".401" class="fostgoobv"/><stop offset=".854" class="g6ymujb6m"/></radialGradient><radialGradient id="ilt3szd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.75 0 0 -2.98124 19.75 18.37)" gradientUnits="userSpaceOnUse"><stop class="ksboejbpj"/><stop offset="1" class="cy3he5b8j"/></radialGradient><radialGradient id="if5R4kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.47529 3.22538 0 20.906 16.096)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="athb14byh"/><stop offset="1" class="dvu1zbcwd"/></radialGradient><radialGradient id="iG1QFmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27427 2.46158 0 12.313 16.457)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="u_avqhqbv"/><stop offset="1" class="t1ajyy0zt"/></radialGradient><radialGradient id="iTiPVMC" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 3.1875 -1.89485 2.21066 14.344 8.714)" gradientUnits="userSpaceOnUse"><stop offset=".015" class="adaz-ibzp"/><stop offset="1" class="jt2u2ab9q"/></radialGradient><radialGradient id="ipnt3ab" cx="0" cy="0" r="1" gradientTransform="rotate(42.842 -7.135 15.943)scale(3.81445 1.99642)" gradientUnits="userSpaceOnUse"><stop class="v0r7enbcn"/><stop offset="1" class="wb6g5gr0v"/></radialGradient><radialGradient id="iq3k5nI" cx="0" cy="0" r="1" gradientTransform="matrix(-.90886 3.10765 -2.35795 -.6896 6.118 9.985)" gradientUnits="userSpaceOnUse"><stop offset=".51" class="eekoomp0i"/><stop offset="1" class="cubw1m9-y"/></radialGradient><radialGradient id="iJRkggc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87501 15.68754 -17.76526 -2.12335 17.438 15.12)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="wnx14ccpe"/><stop offset="1" class="am2--6b1r"/></radialGradient><radialGradient id="i9NIVMW" cx="0" cy="0" r="1" gradientTransform="matrix(-.54687 .9375 -2.00105 -1.16726 10.594 11.152)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="ttficrnrp"/><stop offset="1" class="wsl8ribzw"/></radialGradient><radialGradient id="iU3JUOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.27131 7.31711 0 5.75 16.648)" gradientUnits="userSpaceOnUse"><stop class="xv-x4cbqv"/><stop offset="1" class="uvn51xoxx"/></radialGradient><radialGradient id="iZR1OIc" cx="0" cy="0" r="1" gradientTransform="matrix(2.33333 5.21569 -3.57326 1.59856 25.403 4.303)" gradientUnits="userSpaceOnUse"><stop class="e7pu7cbld"/><stop offset="1" class="pils4iy6q"/></radialGradient><radialGradient id="iPd7gNb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11764 2.4706 -2.32527 -3.87542 9.825 3.205)" gradientUnits="userSpaceOnUse"><stop class="dpsu9cc3s"/><stop offset="1" class="pkbul7lqs"/></radialGradient><radialGradient id="iZslZFD" cx="0" cy="0" r="1" gradientTransform="rotate(28.124 -18.41 13.516)scale(4.51327 6.99061)" gradientUnits="userSpaceOnUse"><stop class="tz-icvb8w"/><stop offset="1" class="e-l_15bec"/></radialGradient><radialGradient id="ioLmPnb" cx="0" cy="0" r="1" gradientTransform="rotate(67.995 9.185 21.99)scale(7.05678 1.94035)" gradientUnits="userSpaceOnUse"><stop class="j66-_kbdd"/><stop offset="1" class="iv9_mc4za"/></radialGradient><radialGradient id="iS4rHSl" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1666 0 0 -.366 16.606 20.762)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="idUfjDZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28125 -2.74 0 15.99 18.804)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="sme3iacos"/><stop offset="1" class="k1jnbwd-y"/></radialGradient><radialGradient id="i0K5k5F" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80763 -2.87524 0 20.326 17.13)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSKW7YZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.51672 -.66586 .91673 -.7114 19.817 17.318)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7FVJ5o" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80073 -2.86427 0 11.64 17.136)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilDBlUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09657 1.31812 -.02064 11.005 17.622)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDjsaPS" cx="0" cy="0" r="1" gradientTransform="matrix(2.71078 -6.38236 10.44465 4.43616 18.918 11.577)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="j2p90_-bc"/><stop offset="1" class="g5d3hjacf"/></radialGradient><radialGradient id="ik8ZS5c" cx="0" cy="0" r="1" gradientTransform="rotate(101.203 7.775 9.96)scale(7.24093 11.8497)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="tm3j_8bvb"/><stop offset="1" class="pft2s7y0a"/></radialGradient><filter id="iWtt7De" width="6.7" height="6.5" x="2.99" y="14.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="ibmIWQc" width="5.24" height="5.24" x="3.62" y="15.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".25"/></filter><filter id="i2WLrve" width="6.75" height="6.75" x="22.51" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="i1xC6Wd" width="5.24" height="5.24" x="23.14" y="15.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".25"/></filter><filter id="ie9MnCe" width="21.5" height="26" x="5.74" y="4.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="iRpOSKd" width="3.67" height="1.492" x="8.93" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.027451 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="iWOpVpd" width="3.37" height="1.192" x="8.98" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".15"/></filter><filter id="imj3gFb" width="3.67" height="1.492" x="19.03" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.027451 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="iahMoOe" width="3.37" height="1.192" x="19.08" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".15"/></filter><filter id="iGA6ILb" width="24.099" height="16.983" x="4.676" y=".979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0588235 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3657"/></filter><filter id="iZ0ah8Q" width="3.905" height="3.717" x="7.96" y="8.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".1"/></filter><filter id="igWWope" width="4.335" height="5.078" x="13.425" y="17.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".25"/></filter><filter id="iTB6Xhb" width="3.997" height="5.016" x="13.992" y="17.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".125"/></filter><filter id="iK271Ed" width="1.507" height="1.306" x="18.813" y="16.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".05"/></filter><filter id="iappXOb" width="1.494" height="1.544" x="20.807" y="16.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".1"/></filter><filter id="iXokObc" width="1.701" height="1.821" x="11.944" y="16.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".1"/></filter><filter id="iF1RMEb" width="1.783" height="1.32" x="10.147" y="16.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".05"/></filter><filter id="i8H5Yqb" width="17.199" height="11.288" x="11.089" y="2.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".5"/></filter><filter id="iIlYtwe" width="1.822" height="3.07" x="11.766" y="6.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".125"/></filter><filter id="i2XDW3d" width="12.438" height="6.453" x="15.76" y="4.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".75"/></filter><filter id="iS4yP3c" width="1.2" height="3.808" x="26.097" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".2"/></filter><filter id="i6R1Hhf" width="1.071" height="3.193" x="11.994" y="8.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".1"/></filter><filter id="i00T1Ic" width="2.91" height="4.214" x="11.998" y="6.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3657" stdDeviation=".1"/></filter><linearGradient id="iv6m9ad" x1="6.24" x2="4.875" y1="18.304" y2="18.304" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iqNq1JR" x1="27.875" x2="26.281" y1="15.585" y2="20.523" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iOUYtid" x1="27.311" x2="24.266" y1="17.021" y2="17.021" gradientUnits="userSpaceOnUse"><stop class="mt5e72-yt"/><stop offset="1" class="au96n9bjd"/></linearGradient><linearGradient id="i97Jtuc" x1="11.656" x2="9.203" y1="13.906" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="iss1cCd" x1="21.756" x2="19.303" y1="13.906" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="iqH9GFb" x1="8.978" x2="11.568" y1="9.061" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient><linearGradient id="iFEwzDb" x1="17.37" x2="16.22" y1="19.382" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></linearGradient><linearGradient id="iVPYmKc" x1="14" x2="15.625" y1="20.804" y2="21.054" gradientUnits="userSpaceOnUse"><stop class="zdhzy27he"/><stop offset="1" class="szy8a_bfr"/></linearGradient><linearGradient id="iEl270b" x1="15.99" x2="15.99" y1="22.07" y2="20.57" gradientUnits="userSpaceOnUse"><stop class="l8cly20bs"/><stop offset="1" class="qg502f0xe"/></linearGradient><linearGradient id="i7SLEQd" x1="22.059" x2="21.36" y1="17.25" y2="17.681" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZpYYnd" x1="13.292" x2="12.595" y1="17.255" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRcHnUc" x1="12.091" x2="14.063" y1="7.151" y2="10.119" gradientUnits="userSpaceOnUse"><stop class="gnc5q69tc"/><stop offset="1" class="m2d_0wb_j"/></linearGradient><linearGradient id="iUq2Ppe" x1="26.543" x2="26.543" y1="16.828" y2="14.271" gradientUnits="userSpaceOnUse"><stop offset=".356" class="gxmgsbm7e"/><stop offset="1" class="hk7638bzn"/></linearGradient><linearGradient id="ivoiTme" x1="12.369" x2="12.604" y1="10.976" y2="8.635" gradientUnits="userSpaceOnUse"><stop offset=".37" class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient><linearGradient id="itk3cih" x1="12.518" x2="14.663" y1="6.447" y2="9.639" gradientUnits="userSpaceOnUse"><stop class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boy-light" /></template>
<style>
.a9ok7vmop {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.43 14.052c.59-.21 1.41-.36 2.47-.26");
}

.adaz-ibzp {
  stop-color: var(--svg-color--ab7a6e, #AB7A6E);
}

.am2--6b1r {
  stop-color: var(--svg-color--b57894, #B57894);
}

.am3a9544w {
  stop-color: var(--svg-color--ffdcc1, #FFDCC1);
}

.athb14byh {
  stop-color: var(--svg-color--f9bdab, #F9BDAB);
}

.au96n9bjd {
  stop-color: var(--svg-color--ffd4b8, #FFD4B8);
  stop-opacity: 0;
}

.awcgk-byh {
  stop-color: var(--svg-color--3d383a, #3D383A);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cubw1m9-y {
  stop-color: var(--svg-color--ad7966, #AD7966);
  stop-opacity: 0;
}

.cy3he5b8j {
  stop-color: var(--svg-color--ffe0c1, #FFE0C1);
  stop-opacity: 0;
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.dpk1kv4yi {
  fill: var(--svg-color--cf928d, #CF928D);
  d: path("m14.047 20.47l1.468-2.268a.426.426 0 0 1 .75.068l.918 2.2h-.009a.72.72 0 0 1-.038.745c-.36.528-.815.87-1.495.87c-.67 0-1.244-.342-1.594-.87c-.176-.262-.15-.514 0-.744");
}

.dpsu9cc3s {
  stop-color: var(--svg-color--434041, #434041);
}

.dtnh3t-ez {
  stroke: var(--svg-color--140e1a, #140E1A);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22 14.052c-.59-.21-1.41-.36-2.47-.26");
}

.dvu1zbcwd {
  stop-color: var(--svg-color--f9bdab, #F9BDAB);
  stop-opacity: 0;
}

.e-l_15bec {
  stop-color: var(--svg-color--514745, #514745);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6e5nabez {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.992 23.134a6.5 6.5 0 0 1-3.016-.733a.328.328 0 0 0-.429.472a4.1 4.1 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.18-.281-.13-.622-.43-.472a6.35 6.35 0 0 1-3.015.733");
}

.e7pu7cbld {
  stop-color: var(--svg-color--4f484b, #4F484B);
}

.eekoomp0i {
  stop-color: var(--svg-color--ad7966, #AD7966);
}

.ekg1bobit {
  stop-color: var(--svg-color--353535, #353535);
  stop-opacity: 0;
}

.f0xgqdvvh {
  d: path("M25.76 20.96a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fostgoobv {
  stop-color: var(--svg-color--eeb8a8, #EEB8A8);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fve6meb5d {
  stop-color: var(--svg-color--3d383a, #3D383A);
}

.fxde6r0oe {
  fill: var(--svg-color--fac4b1, #FAC4B1);
  d: path("m14.363 20.282l1.25-2.604a.412.412 0 0 1 .74-.003l1.309 2.668h-.01a.72.72 0 0 1-.037.744a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.002-.805");
}

.g4-1rtdto {
  fill: var(--svg-color--000, #000);
  d: path("M12.77 18.058a1.13 1.13 0 0 0-1.134-1.135a1.13 1.13 0 0 0-1.134 1.135c0 .189.045.369.126.522h2.008c.08-.153.135-.333.135-.522");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6ymujb6m {
  stop-color: var(--svg-color--d7a296, #D7A296);
}

.g96swhvgt {
  d: path("M22.102 17.794a1.87 1.87 0 0 0-.516-1.03l-.579.635l.261.508z");
}

.gnc5q69tc {
  stop-color: var(--svg-color--261c1c, #261C1C);
}

.grzb5abtp {
  cx: 11.039px;
  cy: 16.923px;
  rx: 0.865px;
  ry: 0.438px;
}

.gxmgsbm7e {
  stop-color: var(--svg-color--3b3739, #3B3739);
}

.h_qkfoevi {
  cx: 11.039px;
  cy: 16.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.865px;
  ry: 0.438px;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.hk7638bzn {
  stop-color: var(--svg-color--3b3739, #3B3739);
  stop-opacity: 0;
}

.i03znbcpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M26.697 17.068V14.46");
}

.ikymlcpqj {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M22.653 6.396h-4.121a1.272 1.272 0 0 0 0 2.544h4.9c2.157 0 3.076.606 3.265.909c-.695-2.763-2.986-3.453-4.044-3.453");
}

.iuv15ibzp {
  d: path("M11.636 16.077a1.98 1.98 0 0 0-1.909 2.503h3.827a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.98");
}

.iv9_mc4za {
  stop-color: var(--svg-color--514b4d, #514B4D);
  stop-opacity: 0;
}

.j_ran_v0u {
  fill: var(--svg-color--e4af9a, #E4AF9A);
  d: path("M25.76 19.83a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j66-_kbdd {
  stop-color: var(--svg-color--514b4d, #514B4D);
}

.j8ttpmb5k {
  d: path("M20.33 16.067a1.988 1.988 0 0 1 1.917 2.513h-3.842a2 2 0 0 1-.072-.524c0-1.094.895-1.989 1.997-1.989");
}

.jeuk3sh0v {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.791 15.462a3.11 3.11 0 0 1 3.02 2.359a.61.61 0 0 1-.597.76h-4.971a.513.513 0 0 1-.507-.606a3.114 3.114 0 0 1 3.055-2.513");
}

.jt2u2ab9q {
  stop-color: var(--svg-color--ab7a6e, #AB7A6E);
  stop-opacity: 0;
}

.k05bo9wuy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.09 6.524c.047.365.35 1.378 1.188 2.516");
}

.k1jnbwd-y {
  stop-color: var(--svg-color--cd8d8e, #CD8D8E);
}

.klmhmr5xc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.177 15.474a3.1 3.1 0 0 0-3.007 2.35a.608.608 0 0 0 .594.756h4.952a.51.51 0 0 0 .504-.603a3.11 3.11 0 0 0-3.043-2.503");
}

.ksboejbpj {
  stop-color: var(--svg-color--ffe0c1, #FFE0C1);
}

.kzjv8db-k {
  fill: var(--svg-color--000, #000);
  d: path("M19.192 18.056c0-.633.506-1.139 1.138-1.139c.633 0 1.14.506 1.14 1.139c0 .19-.046.37-.127.524h-2.016a1.03 1.03 0 0 1-.136-.524");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8cly20bs {
  stop-color: var(--svg-color--d49597, #D49597);
}

.l8ohao8ua {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m2d_0wb_j {
  stop-color: var(--svg-color--261c1c, #261C1C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnsoe0bfo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.398 11.148c-.017-.283 0-1.544.266-2.393");
}

.mt5e72-yt {
  stop-color: var(--svg-color--ffd4b8, #FFD4B8);
}

.n5dtu37fp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.36 8.512c.212.84 1.13 2.601 3.106 2.917");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nwawifxej {
  fill: var(--svg-color--2c2726, #2C2726);
  d: path("m4.704 12.85l.096 4.08c0 .78.668 1.009 1.047 1.033a.093.093 0 0 0 .097-.095L5.89 13.96c0-.61.186-1.286.75-1.812c.578-.54.937-1.086 1.016-1.727c.058-.479.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.342 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.61c.953-.032 3.297.03 5 .171c1.363.113 1.625 1.438 1.625 1.89v3.823a.1.1 0 0 0 .1.1h.113c.49 0 .881-.392.875-.881a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.409-1.89-2.266-2.469-2.562c-.545-.28-.851-.555-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.087-3.703.242c-.735.328-1.454.39-2.657-.188c-1.796-.781-3.453-.36-4.421.688c-.97 1.046-1.985 1.124-2.954 1.53c-.968.407-1.687 1.032-2.64 2.423c-1.264 1.655-1.38 4.53-1.281 5.828");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.ob5n74bcd {
  d: path("M25.76 19.83a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofusybc7o {
  d: path("M17.469 10.994c-3.234 0-5.02-3.74-5.38-5.782c4.688-3.828 10.325-.44 13.528 1.967c2.562 1.925 1.588 4.656.922 5.594c-.227-.813-1.147-1.462-2.164-1.625c-1.36-.22-3.673-.154-6.906-.154");
}

.ox0lmrafs {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M22 14.052c-.59-.21-1.41-.36-2.47-.26");
}

.pa9dn_a9d {
  d: path("M6.24 19.83a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pils4iy6q {
  stop-color: var(--svg-color--4f484b, #4F484B);
  stop-opacity: 0;
}

.pkbul7lqs {
  stop-color: var(--svg-color--434041, #434041);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.qg502f0xe {
  stop-color: var(--svg-color--d49597, #D49597);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r85z0nboo {
  d: path("m14.363 20.282l1.25-2.604a.412.412 0 0 1 .74-.003l1.309 2.668h-.01a.72.72 0 0 1-.037.744a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.002-.805");
}

.sdrp4rbiu {
  stroke: var(--svg-color--140e1a, #140E1A);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.43 14.052c.59-.21 1.41-.36 2.47-.26");
}

.sme3iacos {
  stop-color: var(--svg-color--cd8d8e, #CD8D8E);
  stop-opacity: 0;
}

.szy8a_bfr {
  stop-color: var(--svg-color--dea790, #DEA790);
  stop-opacity: 0;
}

.t1ajyy0zt {
  stop-color: var(--svg-color--cf968e, #CF968E);
  stop-opacity: 0;
}

.tm3j_8bvb {
  stop-color: var(--svg-color--221c27, #221C27);
  stop-opacity: 0;
}

.ttficrnrp {
  stop-color: var(--svg-color--b28075, #B28075);
}

.tz-icvb8w {
  stop-color: var(--svg-color--514745, #514745);
}

.u_avqhqbv {
  stop-color: var(--svg-color--cf968e, #CF968E);
}

.uv5y5wpjp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.184 16.488c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.uvn51xoxx {
  stop-color: var(--svg-color--1a151a, #1A151A);
  stop-opacity: 0;
}

.v0r7enbcn {
  stop-color: var(--svg-color--b48276, #B48276);
}

.vmna15bfy {
  d: path("M20.184 16.488c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wb6g5gr0v {
  stop-color: var(--svg-color--b48276, #B48276);
  stop-opacity: 0;
}

.wcydw6b9p {
  d: path("M13.446 17.825c0-.64-.52-1.067-.661-1.196l-.64.62l.393.801z");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wgy5ihboo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.398 6.447c.23.761.972 2.509 2.11 3.415");
}

.wnx14ccpe {
  stop-color: var(--svg-color--b57894, #B57894);
  stop-opacity: 0;
}

.wsl8ribzw {
  stop-color: var(--svg-color--b28075, #B28075);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xv-x4cbqv {
  stop-color: var(--svg-color--1a151a, #1A151A);
}

.xxsp33bgf {
  d: path("M13.386 4.021c-4.343 0-7.819 3.631-7.64 7.993l.28 8.223c.239 5.853 4.63 9.784 9.969 9.784s9.73-3.931 9.97-9.784l.083-4.13l.185-4.093c.18-4.362-3.296-7.993-7.639-7.993z");
}

.yfcig1bqm {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
}

.z3krmcchz {
  d: path("M6.24 20.96a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.zb1lfmbev {
  d: path("m4.704 12.85l.096 4.08c0 .78.668 1.009 1.047 1.033a.093.093 0 0 0 .097-.095L5.89 13.96c0-.61.186-1.286.75-1.812c.578-.54.937-1.086 1.016-1.727c.058-.479.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.342 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.61c.953-.032 3.297.03 5 .171c1.363.113 1.625 1.438 1.625 1.89v3.823a.1.1 0 0 0 .1.1h.113c.49 0 .881-.392.875-.881a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.409-1.89-2.266-2.469-2.562c-.545-.28-.851-.555-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.087-3.703.242c-.735.328-1.454.39-2.657-.188c-1.796-.781-3.453-.36-4.421.688c-.97 1.046-1.985 1.124-2.954 1.53c-.968.407-1.687 1.032-2.64 2.423c-1.264 1.655-1.38 4.53-1.281 5.828");
}

.zdhzy27he {
  stop-color: var(--svg-color--dea790, #DEA790);
}

</style>
