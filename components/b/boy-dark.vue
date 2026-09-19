<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWld6wd)"><path fill="url(#iCjoxvc)" class="z3krmcchz"/></g><g filter="url(#iol9S9J)"><path fill="url(#iS5wmDH)" class="pa9dn_a9d"/></g><g filter="url(#i5BUgkw)"><path fill="url(#ioinUtc)" class="f0xgqdvvh"/><path fill="url(#in6RIOj)" class="f0xgqdvvh"/></g><g filter="url(#iGSWElc)"><path class="m85q3kbwo"/><path fill="url(#igWVCRd)" class="ob5n74bcd"/><path fill="url(#i4rgwCd)" class="ob5n74bcd"/></g><g filter="url(#iH18Aze)"><path fill="url(#igjyMDd)" class="xxsp33bgf"/><path fill="url(#icnpJpc)" class="xxsp33bgf"/><path fill="url(#i4eVmJc)" class="xxsp33bgf"/><path fill="url(#ijZlCHe)" class="xxsp33bgf"/><path fill="url(#iWJtx4c)" class="xxsp33bgf"/><path fill="url(#igbi5Cc)" class="xxsp33bgf"/></g><path fill="url(#iFB9hBc)" class="xxsp33bgf"/><path fill="url(#iHp8fPd)" class="xxsp33bgf"/><path fill="url(#ijdoBgd)" class="xxsp33bgf"/><path fill="url(#iItkTWc)" class="xxsp33bgf"/><path fill="url(#ifE8Qye)" class="xxsp33bgf"/><path fill="url(#iav1gme)" class="xxsp33bgf"/><path class="c7ms_bcct"/><g filter="url(#ivCMBtd)"><path class="sdrp4rbiu"/></g><g filter="url(#ixNr0se)"><path stroke="url(#i97Jtuc)" class="a9ok7vmop"/></g><g filter="url(#iv2FlXb)"><path class="dtnh3t-ez"/></g><g filter="url(#ilOA2Dc)"><path stroke="url(#iss1cCd)" class="ox0lmrafs"/></g><g filter="url(#ihb4I2E)"><path class="jl03pab6p"/><path fill="url(#iU3JUOd)" class="pfn064b4a"/><path fill="url(#iZR1OIc)" class="pfn064b4a"/><path fill="url(#iPd7gNb)" class="pfn064b4a"/><path fill="url(#iZslZFD)" class="pfn064b4a"/><path fill="url(#ioLmPnb)" class="pfn064b4a"/></g><g filter="url(#ilcuQRd)"><path stroke="url(#iqH9GFb)" class="n5dtu37fp"/></g><g filter="url(#ipIEibe)"><path class="luhanj_1t"/></g><g filter="url(#izCbiub)"><path class="t2_h92bdp"/><path fill="url(#iJTW4Fc)" class="r85z0nboo"/><path fill="url(#ivsnn6c)" class="r85z0nboo"/><path fill="url(#igE3jhX)" class="r85z0nboo"/><path fill="url(#i0uqPUb)" class="r85z0nboo"/></g><path fill="url(#iqEBFoc)" class="r85z0nboo"/><path class="x70bebcio"/><path fill="url(#i0K5k5F)" class="j8ttpmb5k"/><path class="kzjv8db-k"/><g filter="url(#inDxLtc)"><path class="uv5y5wpjp"/><path fill="url(#iSKW7YZ)" class="vmna15bfy"/></g><g filter="url(#i5Qr38K)"><path fill="url(#i7SLEQd)" class="g96swhvgt"/></g><path class="klmhmr5xc"/><path fill="url(#i7FVJ5o)" class="iuv15ibzp"/><path class="g4-1rtdto"/><g filter="url(#iHM3nfd)"><path fill="url(#iZpYYnd)" class="wcydw6b9p"/></g><g filter="url(#i8uQBie)"><ellipse transform="rotate(-27.914 11.039 16.923)" class="h_qkfoevi"/><ellipse fill="url(#ilDBlUd)" transform="rotate(-27.914 11.039 16.923)" class="grzb5abtp"/></g><g filter="url(#iD7qUMd)"><path fill="url(#iDjsaPS)" class="ofusybc7o"/><path fill="url(#ialI7rc)" class="ofusybc7o"/></g><g filter="url(#iqQJqHc)"><path stroke="url(#iRcHnUc)" class="k05bo9wuy"/></g><g filter="url(#iQeUmgr)"><path class="ikymlcpqj"/></g><g filter="url(#iRV4EYb)"><path stroke="url(#iUq2Ppe)" class="i03znbcpp"/></g><g filter="url(#iBoj15b)"><path stroke="url(#ivoiTme)" class="mnsoe0bfo"/></g><g filter="url(#iX2Vttc)"><path stroke="url(#itk3cih)" class="wgy5ihboo"/></g><defs><radialGradient id="iCjoxvc" cx="0" cy="0" r="1" gradientTransform="matrix(3.41626 0 0 5.97849 2.99 17.71)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="in6RIOj" cx="0" cy="0" r="1" gradientTransform="matrix(1.60937 -1.17187 1.33754 1.8369 26.484 17.195)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="igWVCRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -3.21875 1.88395 1.02428 25.672 19.46)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i4rgwCd" cx="0" cy="0" r="1" gradientTransform="matrix(.55251 .5469 -.70503 .71226 25.76 17.71)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="igjyMDd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.25009 7.91165 -8.96041 -17.27163 22.938 17.021)" gradientUnits="userSpaceOnUse"><stop class="wnlrhdrlt"/><stop offset=".401" class="tf2lr1bmh"/><stop offset=".854" class="id4--kb6v"/></radialGradient><radialGradient id="icnpJpc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.75 0 0 -2.98124 19.75 18.37)" gradientUnits="userSpaceOnUse"><stop class="zpqiekbmq"/><stop offset="1" class="bd9nggb_d"/></radialGradient><radialGradient id="i4eVmJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.47529 3.22538 0 20.906 16.096)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="utc-9sb2o"/><stop offset="1" class="uxamr82cb"/></radialGradient><radialGradient id="ijZlCHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27427 2.46158 0 12.313 16.457)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="a2wp9jy4q"/><stop offset="1" class="sxctt6bkr"/></radialGradient><radialGradient id="iWJtx4c" cx="0" cy="0" r="1" gradientTransform="rotate(111.736 6.112 11.752)scale(7.0989 5.00414)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="k9gn-acfz"/><stop offset="1" class="c81154bqj"/></radialGradient><radialGradient id="iFB9hBc" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 3.1875 -1.89485 2.21066 14.344 8.714)" gradientUnits="userSpaceOnUse"><stop offset=".015" class="kh9z4xb5m"/><stop offset="1" class="b-edavilb"/></radialGradient><radialGradient id="iHp8fPd" cx="0" cy="0" r="1" gradientTransform="rotate(42.842 -7.135 15.943)scale(3.81445 1.99642)" gradientUnits="userSpaceOnUse"><stop class="h-wu0ubdp"/><stop offset="1" class="d5n9-25ix"/></radialGradient><radialGradient id="ijdoBgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4903 2.9806 -2.34233 -1.17116 6.7 10.112)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="h-wu0ubdp"/><stop offset="1" class="d5n9-25ix"/></radialGradient><radialGradient id="iItkTWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87501 15.68754 -17.76526 -2.12335 17.438 15.12)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="g2baapiwg"/><stop offset="1" class="xjlp3iblu"/></radialGradient><radialGradient id="ifE8Qye" cx="0" cy="0" r="1" gradientTransform="matrix(-.54687 .9375 -2.00105 -1.16726 10.594 11.152)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="a22t-0bbq"/><stop offset="1" class="wqcz94q3b"/></radialGradient><radialGradient id="iav1gme" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.4619 -12.3297 0 15.99 17.021)" gradientUnits="userSpaceOnUse"><stop offset=".892" class="lqb3v3b6a"/><stop offset="1" class="c6qauqb8h"/></radialGradient><radialGradient id="iU3JUOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.27131 7.31711 0 5.75 16.648)" gradientUnits="userSpaceOnUse"><stop class="xv-x4cbqv"/><stop offset="1" class="uvn51xoxx"/></radialGradient><radialGradient id="iZR1OIc" cx="0" cy="0" r="1" gradientTransform="matrix(2.33333 5.21569 -3.57326 1.59856 25.403 4.303)" gradientUnits="userSpaceOnUse"><stop class="e7pu7cbld"/><stop offset="1" class="pils4iy6q"/></radialGradient><radialGradient id="iPd7gNb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11764 2.4706 -2.32527 -3.87542 9.825 3.205)" gradientUnits="userSpaceOnUse"><stop class="dpsu9cc3s"/><stop offset="1" class="pkbul7lqs"/></radialGradient><radialGradient id="iZslZFD" cx="0" cy="0" r="1" gradientTransform="rotate(28.124 -18.41 13.516)scale(4.51327 6.99061)" gradientUnits="userSpaceOnUse"><stop class="tz-icvb8w"/><stop offset="1" class="e-l_15bec"/></radialGradient><radialGradient id="ioLmPnb" cx="0" cy="0" r="1" gradientTransform="rotate(67.995 9.185 21.99)scale(7.05678 1.94035)" gradientUnits="userSpaceOnUse"><stop class="j66-_kbdd"/><stop offset="1" class="iv9_mc4za"/></radialGradient><radialGradient id="i0uqPUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1666 0 0 -.366 16.606 20.762)" gradientUnits="userSpaceOnUse"><stop class="m7i9z2bnn"/><stop offset="1" class="m5l6agbgw"/></radialGradient><radialGradient id="iqEBFoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28125 -2.74 0 15.99 18.804)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="ulusgx5sc"/><stop offset="1" class="nvjbx51eh"/></radialGradient><radialGradient id="i0K5k5F" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80763 -2.87524 0 20.326 17.13)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSKW7YZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.51672 -.66586 .91673 -.7114 19.817 17.318)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7FVJ5o" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.80073 -2.86427 0 11.64 17.136)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilDBlUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01717 -1.09657 1.31812 -.02064 11.005 17.622)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDjsaPS" cx="0" cy="0" r="1" gradientTransform="matrix(2.71078 -6.38236 10.44465 4.43616 18.918 11.577)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="j2p90_-bc"/><stop offset="1" class="g5d3hjacf"/></radialGradient><radialGradient id="ialI7rc" cx="0" cy="0" r="1" gradientTransform="rotate(101.203 7.775 9.96)scale(7.24093 11.8497)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="l19i1ibwt"/><stop offset="1" class="zjrk9acqs"/></radialGradient><filter id="iWld6wd" width="6.7" height="6.5" x="2.99" y="14.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="iol9S9J" width="5.24" height="5.24" x="3.62" y="15.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".25"/></filter><filter id="i5BUgkw" width="6.75" height="6.75" x="22.51" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="iGSWElc" width="5.24" height="5.24" x="23.14" y="15.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".25"/></filter><filter id="iH18Aze" width="21.5" height="26" x="5.74" y="4.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="ivCMBtd" width="3.67" height="1.492" x="8.93" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.027451 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="ixNr0se" width="3.37" height="1.192" x="8.98" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".15"/></filter><filter id="iv2FlXb" width="3.67" height="1.492" x="19.03" y="13.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.027451 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="ilOA2Dc" width="3.37" height="1.192" x="19.08" y="13.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".15"/></filter><filter id="ihb4I2E" width="24.099" height="16.983" x="4.676" y=".979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0588235 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3653"/></filter><filter id="ilcuQRd" width="3.905" height="3.717" x="7.96" y="8.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".1"/></filter><filter id="ipIEibe" width="4.335" height="5.078" x="13.425" y="17.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".25"/></filter><filter id="izCbiub" width="3.997" height="5.016" x="13.992" y="17.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".125"/></filter><filter id="inDxLtc" width="1.507" height="1.306" x="18.813" y="16.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".05"/></filter><filter id="i5Qr38K" width="1.494" height="1.544" x="20.807" y="16.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".1"/></filter><filter id="iHM3nfd" width="1.701" height="1.821" x="11.944" y="16.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".1"/></filter><filter id="i8uQBie" width="1.783" height="1.32" x="10.147" y="16.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".05"/></filter><filter id="iD7qUMd" width="17.199" height="11.288" x="11.089" y="2.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".5"/></filter><filter id="iqQJqHc" width="1.822" height="3.07" x="11.766" y="6.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".125"/></filter><filter id="iQeUmgr" width="12.438" height="6.453" x="15.76" y="4.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".75"/></filter><filter id="iRV4EYb" width="1.2" height="3.808" x="26.097" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".2"/></filter><filter id="iBoj15b" width="1.071" height="3.193" x="11.994" y="8.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".1"/></filter><filter id="iX2Vttc" width="2.91" height="4.214" x="11.998" y="6.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3653" stdDeviation=".1"/></filter><linearGradient id="iS5wmDH" x1="6.24" x2="4.875" y1="18.304" y2="18.304" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="ioinUtc" x1="27.875" x2="26.281" y1="15.585" y2="20.523" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="igbi5Cc" x1="27.311" x2="23.105" y1="17.021" y2="17.021" gradientUnits="userSpaceOnUse"><stop class="d0kv1cyul"/><stop offset="1" class="iboeeybhd"/></linearGradient><linearGradient id="i97Jtuc" x1="11.656" x2="9.203" y1="13.906" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="iss1cCd" x1="21.756" x2="19.303" y1="13.906" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="d_wzpg_av"/><stop offset="1" class="ekg1bobit"/></linearGradient><linearGradient id="iqH9GFb" x1="8.978" x2="11.568" y1="9.061" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient><linearGradient id="iJTW4Fc" x1="17.37" x2="16.22" y1="19.382" y2="19.53" gradientUnits="userSpaceOnUse"><stop class="ynf5v8bww"/><stop offset="1" class="dbni4sbmg"/></linearGradient><linearGradient id="ivsnn6c" x1="14" x2="15.625" y1="20.804" y2="21.054" gradientUnits="userSpaceOnUse"><stop class="t__2ntb2z"/><stop offset="1" class="u89wzqwco"/></linearGradient><linearGradient id="igE3jhX" x1="15.99" x2="15.99" y1="22.07" y2="20.57" gradientUnits="userSpaceOnUse"><stop class="hh7s4gb1i"/><stop offset="1" class="cp_efbcin"/></linearGradient><linearGradient id="i7SLEQd" x1="22.059" x2="21.36" y1="17.25" y2="17.681" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZpYYnd" x1="13.292" x2="12.595" y1="17.255" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRcHnUc" x1="12.091" x2="14.063" y1="7.151" y2="10.119" gradientUnits="userSpaceOnUse"><stop class="gnc5q69tc"/><stop offset="1" class="m2d_0wb_j"/></linearGradient><linearGradient id="iUq2Ppe" x1="26.543" x2="26.543" y1="16.828" y2="14.271" gradientUnits="userSpaceOnUse"><stop offset=".356" class="gxmgsbm7e"/><stop offset="1" class="hk7638bzn"/></linearGradient><linearGradient id="ivoiTme" x1="12.369" x2="12.604" y1="10.976" y2="8.635" gradientUnits="userSpaceOnUse"><stop offset=".37" class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient><linearGradient id="itk3cih" x1="12.518" x2="14.663" y1="6.447" y2="9.639" gradientUnits="userSpaceOnUse"><stop class="fve6meb5d"/><stop offset="1" class="awcgk-byh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boy-dark" /></template>
<style>
.a22t-0bbq {
  stop-color: var(--svg-color--2c1b1d, #2C1B1D);
}

.a2wp9jy4q {
  stop-color: var(--svg-color--351f25, #351F25);
}

.a9ok7vmop {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.43 14.052c.59-.21 1.41-.36 2.47-.26");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.awcgk-byh {
  stop-color: var(--svg-color--3d383a, #3D383A);
  stop-opacity: 0;
}

.b-edavilb {
  stop-color: var(--svg-color--27181a, #27181A);
  stop-opacity: 0;
}

.bd9nggb_d {
  stop-color: var(--svg-color--543733, #543733);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c6qauqb8h {
  stop-color: var(--svg-color--5f4b66, #5F4B66);
}

.c7ms_bcct {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.992 23.134a6.5 6.5 0 0 1-3.016-.733a.328.328 0 0 0-.429.472a4.1 4.1 0 0 0 3.445 1.887a4.1 4.1 0 0 0 3.445-1.887c.18-.281-.13-.622-.43-.472a6.35 6.35 0 0 1-3.015.733");
}

.c81154bqj {
  stop-color: var(--svg-color--4a393a, #4A393A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp_efbcin {
  stop-color: var(--svg-color--3b2030, #3B2030);
  stop-opacity: 0;
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d5n9-25ix {
  stop-color: var(--svg-color--180a0a, #180A0A);
  stop-opacity: 0;
}

.dbni4sbmg {
  stop-color: var(--svg-color--624f4d, #624F4D);
  stop-opacity: 0;
}

.dpsu9cc3s {
  stop-color: var(--svg-color--434041, #434041);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dtnh3t-ez {
  stroke: var(--svg-color--140e1a, #140E1A);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M22 14.052c-.59-.21-1.41-.36-2.47-.26");
}

.e-l_15bec {
  stop-color: var(--svg-color--514745, #514745);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7pu7cbld {
  stop-color: var(--svg-color--4f484b, #4F484B);
}

.ekg1bobit {
  stop-color: var(--svg-color--353535, #353535);
  stop-opacity: 0;
}

.f0xgqdvvh {
  d: path("M25.76 20.96a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fve6meb5d {
  stop-color: var(--svg-color--3d383a, #3D383A);
}

.g2baapiwg {
  stop-color: var(--svg-color--3f233c, #3F233C);
  stop-opacity: 0;
}

.g4-1rtdto {
  fill: var(--svg-color--000, #000);
  d: path("M12.77 18.058a1.13 1.13 0 0 0-1.134-1.135a1.13 1.13 0 0 0-1.134 1.135c0 .189.045.369.126.522h2.008c.08-.153.135-.333.135-.522");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
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

.h-wu0ubdp {
  stop-color: var(--svg-color--180a0a, #180A0A);
}

.hh7s4gb1i {
  stop-color: var(--svg-color--3b2030, #3B2030);
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

.iboeeybhd {
  stop-color: var(--svg-color--5b4542, #5B4542);
  stop-opacity: 0;
}

.id4--kb6v {
  stop-color: var(--svg-color--382526, #382526);
}

.ikymlcpqj {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M22.653 6.396h-4.121a1.272 1.272 0 0 0 0 2.544h4.9c2.157 0 3.076.606 3.265.909c-.695-2.763-2.986-3.453-4.044-3.453");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iuv15ibzp {
  d: path("M11.636 16.077a1.98 1.98 0 0 0-1.909 2.503h3.827a2 2 0 0 0 .072-.522a1.994 1.994 0 0 0-1.99-1.98");
}

.iv9_mc4za {
  stop-color: var(--svg-color--514b4d, #514B4D);
  stop-opacity: 0;
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

.jl03pab6p {
  fill: var(--svg-color--23191d, #23191D);
  d: path("m4.704 12.85l.096 4.08c0 .78.668 1.009 1.047 1.033a.092.092 0 0 0 .097-.095L5.89 13.96c0-.61.186-1.286.75-1.812c.578-.54.937-1.086 1.016-1.727c.058-.479.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.342 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.61c.953-.032 3.297.03 5 .171c1.363.113 1.625 1.438 1.625 1.89v3.823a.1.1 0 0 0 .1.1h.113c.49 0 .881-.392.875-.881a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.409-1.89-2.265-2.469-2.562c-.545-.28-.851-.555-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.087-3.703.242c-.735.328-1.454.39-2.657-.188c-1.796-.781-3.453-.36-4.421.688c-.97 1.046-1.985 1.125-2.954 1.53c-.968.407-1.687 1.032-2.64 2.423c-1.264 1.655-1.38 4.53-1.281 5.828");
}

.k05bo9wuy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.09 6.524c.047.365.35 1.378 1.188 2.516");
}

.k9gn-acfz {
  stop-color: var(--svg-color--4a393a, #4A393A);
}

.kh9z4xb5m {
  stop-color: var(--svg-color--27181a, #27181A);
}

.klmhmr5xc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.177 15.474a3.1 3.1 0 0 0-3.007 2.35a.608.608 0 0 0 .594.756h4.952a.51.51 0 0 0 .504-.603a3.11 3.11 0 0 0-3.043-2.503");
}

.kzjv8db-k {
  fill: var(--svg-color--000, #000);
  d: path("M19.192 18.056c0-.633.506-1.139 1.138-1.139c.633 0 1.14.506 1.14 1.139c0 .19-.046.37-.127.524h-2.016a1.03 1.03 0 0 1-.136-.524");
}

.l19i1ibwt {
  stop-color: var(--svg-color--261327, #261327);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqb3v3b6a {
  stop-color: var(--svg-color--5f4b66, #5F4B66);
  stop-opacity: 0;
}

.luhanj_1t {
  fill: var(--svg-color--331e25, #331E25);
  d: path("m14.047 20.47l1.468-2.268a.426.426 0 0 1 .75.068l.918 2.2h-.009a.72.72 0 0 1-.038.745c-.36.528-.815.87-1.495.87c-.67 0-1.244-.342-1.594-.87c-.176-.262-.15-.514 0-.744");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m2d_0wb_j {
  stop-color: var(--svg-color--261c1c, #261C1C);
  stop-opacity: 0;
}

.m5l6agbgw {
  stop-color: var(--svg-color--665352, #665352);
  stop-opacity: 0;
}

.m7i9z2bnn {
  stop-color: var(--svg-color--665352, #665352);
}

.m85q3kbwo {
  fill: var(--svg-color--463133, #463133);
  d: path("M25.76 19.83a2.12 2.12 0 1 0 0-4.24a2.12 2.12 0 0 0 0 4.24");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnsoe0bfo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.398 11.148c-.017-.283 0-1.544.266-2.393");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n5dtu37fp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.36 8.512c.212.84 1.13 2.601 3.106 2.917");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nvjbx51eh {
  stop-color: var(--svg-color--311721, #311721);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
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

.pfn064b4a {
  d: path("m4.704 12.85l.096 4.08c0 .78.668 1.009 1.047 1.033a.092.092 0 0 0 .097-.095L5.89 13.96c0-.61.186-1.286.75-1.812c.578-.54.937-1.086 1.016-1.727c.058-.479.152-.735.24-.895c.065-.117.283-.09.341.03c.846 1.763 2.454 2.342 3.672 2.434c.538.04.912-.456.909-.996c-.005-.708.064-1.405.197-1.643c2.203 2.703 5.422 2.64 6.375 2.61c.953-.032 3.297.03 5 .171c1.363.113 1.625 1.438 1.625 1.89v3.823a.1.1 0 0 0 .1.1h.113c.49 0 .881-.392.875-.881a34 34 0 0 1 .006-1.776c.047-1.14.015-1.344.828-2.89c.707-1.346 1.086-2.282.656-3.938c-.366-1.409-1.89-2.265-2.469-2.562c-.545-.28-.851-.555-1.117-1.07c-.265-.516-.644-1.66-2.648-2.5c-1.79-.75-2.969-.087-3.703.242c-.735.328-1.454.39-2.657-.188c-1.796-.781-3.453-.36-4.421.688c-.97 1.046-1.985 1.125-2.954 1.53c-.968.407-1.687 1.032-2.64 2.423c-1.264 1.655-1.38 4.53-1.281 5.828");
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

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
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

.sxctt6bkr {
  stop-color: var(--svg-color--351f25, #351F25);
  stop-opacity: 0;
}

.t__2ntb2z {
  stop-color: var(--svg-color--3d2927, #3D2927);
}

.t2_h92bdp {
  fill: var(--svg-color--482f2d, #482F2D);
  d: path("m14.363 20.282l1.25-2.604a.412.412 0 0 1 .74-.003l1.309 2.668h-.01a.72.72 0 0 1-.037.744a1.946 1.946 0 0 1-3.25 0a.72.72 0 0 1-.002-.805");
}

.tf2lr1bmh {
  stop-color: var(--svg-color--4a2d2e, #4A2D2E);
}

.tz-icvb8w {
  stop-color: var(--svg-color--514745, #514745);
}

.u89wzqwco {
  stop-color: var(--svg-color--3d2927, #3D2927);
  stop-opacity: 0;
}

.ulusgx5sc {
  stop-color: var(--svg-color--311721, #311721);
  stop-opacity: 0;
}

.utc-9sb2o {
  stop-color: var(--svg-color--45292a, #45292A);
}

.uv5y5wpjp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.184 16.488c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.uvn51xoxx {
  stop-color: var(--svg-color--1a151a, #1A151A);
  stop-opacity: 0;
}

.uxamr82cb {
  stop-color: var(--svg-color--45292a, #45292A);
  stop-opacity: 0;
}

.vmna15bfy {
  d: path("M20.184 16.488c.142.19-.154.42-.491.672s-.587.429-.728.24c-.142-.19.016-.548.353-.8c.337-.251.724-.302.866-.112");
}

.wcydw6b9p {
  d: path("M13.446 17.825c0-.64-.52-1.067-.661-1.196l-.64.62l.393.801z");
}

.wgy5ihboo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.398 6.447c.23.761.972 2.509 2.11 3.415");
}

.wnlrhdrlt {
  stop-color: var(--svg-color--51332f, #51332F);
}

.wqcz94q3b {
  stop-color: var(--svg-color--2c1b1d, #2C1B1D);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x70bebcio {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.791 15.462a3.11 3.11 0 0 1 3.02 2.359a.61.61 0 0 1-.597.76h-4.971a.513.513 0 0 1-.507-.607a3.114 3.114 0 0 1 3.055-2.512");
}

.xjlp3iblu {
  stop-color: var(--svg-color--3f233c, #3F233C);
}

.xv-x4cbqv {
  stop-color: var(--svg-color--1a151a, #1A151A);
}

.xxsp33bgf {
  d: path("M13.386 4.021c-4.343 0-7.819 3.631-7.64 7.993l.28 8.223c.239 5.853 4.63 9.784 9.969 9.784s9.73-3.931 9.97-9.784l.083-4.13l.185-4.093c.18-4.362-3.296-7.993-7.639-7.993z");
}

.ynf5v8bww {
  stop-color: var(--svg-color--624f4d, #624F4D);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.z3krmcchz {
  d: path("M6.24 20.96a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.zjrk9acqs {
  stop-color: var(--svg-color--261327, #261327);
}

.zpqiekbmq {
  stop-color: var(--svg-color--543733, #543733);
}

</style>
