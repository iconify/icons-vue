<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ceu41zgqi"/><path fill="url(#iDQvaPc)" class="xdm34lb1w"/><path class="wrawjn1dr"/><path fill="url(#iDOwCXb)" class="ltmziab0x"/><path fill="url(#iEjD3De)" class="ltmziab0x"/><g filter="url(#iKdZv8b)"><path clip-rule="evenodd" class="y4zkhtrvy"/></g><path clip-rule="evenodd" class="bk3c8_nkf"/><path fill="url(#iBw4GGb)" clip-rule="evenodd" class="z-9besbip"/><path fill="url(#ipIzrLd)" clip-rule="evenodd" class="z-9besbip"/><path fill="url(#igokA8H)" clip-rule="evenodd" class="z-9besbip"/><g clip-rule="evenodd" filter="url(#ii7Gjkb)" class="d2kvgvbvc"><path class="g5n_9-2kf"/><path fill="url(#ijZeAob)" class="kr30-n81j"/></g><g filter="url(#i1SdFVb)"><path clip-rule="evenodd" class="ruqe6ccbr"/></g><path clip-rule="evenodd" class="oy1j_vybm"/><path fill="url(#ihI0qJb)" clip-rule="evenodd" class="h1_ce3bdi"/><path fill="url(#iK2dGYv)" clip-rule="evenodd" class="h1_ce3bdi"/><path fill="url(#i7h8ilN)" clip-rule="evenodd" class="h1_ce3bdi"/><path fill="url(#ionSY9d)" clip-rule="evenodd" class="h1_ce3bdi"/><path fill="url(#ie8kgHe)" clip-rule="evenodd" class="h1_ce3bdi"/><g filter="url(#iiGtsyc)"><path class="ye0l8g_nn"/></g><g filter="url(#iejPN6b)"><path class="mncfu1f8v"/></g><g filter="url(#i1pvymc)"><path class="dlt1iu2hi"/></g><g filter="url(#i4D1JJc)"><path class="g7-w8d-ss"/></g><g filter="url(#iXxDMvb)"><path fill="url(#i4YxYIe)" clip-rule="evenodd" class="sie_6lv-d"/></g><path class="zeldscc-t"/><path fill="url(#iTRoG5d)" class="tfzk03bbr"/><path fill="url(#iNGoR4d)" class="tfzk03bbr"/><g filter="url(#i9Llqfc)"><path fill="url(#iRzDtPb)" class="l5xjzmead"/><path class="wmwpc4bob"/></g><path fill="url(#ivpriqc)" class="f8u124bzp"/><path fill="url(#iHVLxlc)" class="f8u124bzp"/><g filter="url(#iZV7Uqb)"><path class="q2kk8z4gy"/></g><g filter="url(#iu2FLyb)"><path class="nexn4bbdt"/></g><path class="wibpf9bsc"/><path fill="url(#ipuyAVc)" class="d-s162mcz"/><path fill="url(#icuPwfe)" class="d-s162mcz"/><path class="zo9q5bcpb"/><path fill="url(#islRVpg)" class="nmv-xubvf"/><path fill="url(#ihJZXob)" class="nmv-xubvf"/><g filter="url(#iYLurGb)"><path fill="url(#iOzGdRd)" class="p-vld3bbr"/></g><path fill="url(#ijdBLfc)" class="cb961vf9n"/><path fill="url(#isOxcGe)" class="cb961vf9n"/><path class="jaj6zizdf"/><path fill="url(#iqKPffc)" class="w53opvb2z"/><path fill="url(#iV9xhgj)" class="w53opvb2z"/><g filter="url(#inAJVVy)"><path class="u7h7ggb1e"/></g><path class="udkxz2b2f"/><path fill="url(#iZF7Ckb)" class="my1djhb1t"/><path fill="url(#iehlBQd)" class="my1djhb1t"/><g filter="url(#i3GAboc)"><path class="uej01l3sj"/></g><path fill="url(#i9xdynd)" class="vi3oveb0y"/><path fill="url(#i82xy0b)" class="vi3oveb0y"/><g filter="url(#iXHurAG)"><path class="xy79f-cvq"/></g><path fill="url(#iEq0moc)" class="xbkoqgsls"/><path fill="url(#iwprcNc)" class="xbkoqgsls"/><g filter="url(#iRCuV7c)"><path class="bmftbqbmc"/></g><g filter="url(#itB72de)"><path class="nclwnzwln"/></g><path fill="url(#ijyivKf)" class="crswi9b3q"/><path fill="url(#iUcE7xo)" class="crswi9b3q"/><g filter="url(#inq507b)"><path class="nd81gmbsd"/></g><path class="bqwpzsk1s"/><path fill="url(#i6NOQhs)" class="ohusp2buq"/><path fill="url(#i4axKhd)" class="ohusp2buq"/><path class="xtvew8b3p"/><path fill="url(#iH5ZCxe)" class="u7fvtbbna"/><path fill="url(#ip8Q8Hc)" class="u7fvtbbna"/><g filter="url(#i1f2GpY)"><path class="glwxidbit"/></g><g filter="url(#i0vwIjO)"><path fill="url(#iCz9bmb)" class="ggktdrf8w"/><path class="wrbo5hgkv"/></g><path fill="url(#iOSjhRb)" class="cdcfgobfz"/><path fill="url(#iCyC9Kb)" class="cdcfgobfz"/><path fill="url(#irpr0ow)" class="gf9eyc_lq"/><path fill="url(#itLYR4b)" class="gf9eyc_lq"/><path class="lpy1urbik"/><path fill="url(#iPzNM8b)" class="jqko2-7cm"/><path fill="url(#i28byRd)" class="jqko2-7cm"/><path class="l16v13b1y"/><path fill="url(#ius4cSZ)" class="iqwotzb2m"/><path fill="url(#i2nI88b)" class="iqwotzb2m"/><defs><radialGradient id="iDQvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5625 -2.57732 0 20.25 18.313)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="j6fj6ib9k"/><stop offset=".829" class="uakpcckis"/></radialGradient><radialGradient id="iDOwCXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.4374 -11.2435 0 19.484 19.563)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="fjciawbop"/><stop offset=".982" class="zzaddacea"/></radialGradient><radialGradient id="iEjD3De" cx="0" cy="0" r="1" gradientTransform="matrix(1.2752 6.8125 -6.88863 1.28946 9.975 20.625)" gradientUnits="userSpaceOnUse"><stop offset=".51" class="s3alhcb7x"/><stop offset="1" class="kz7zanbcd"/></radialGradient><radialGradient id="ipIzrLd" cx="0" cy="0" r="1" gradientTransform="rotate(119.347 -.224 15.01)scale(6.95508 7.30215)" gradientUnits="userSpaceOnUse"><stop class="rcf9jfa-u"/><stop offset="1" class="nql8ltbxc"/></radialGradient><radialGradient id="igokA8H" cx="0" cy="0" r="1" gradientTransform="matrix(5.21876 -2.40621 2.5263 5.4792 12.156 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="sog9u6bia"/><stop offset=".485" class="a4zifxbhr"/><stop offset=".753" class="hqyy7cc4w"/><stop offset="1" class="lhy0o8buo"/></radialGradient><radialGradient id="ijZeAob" cx="0" cy="0" r="1" gradientTransform="rotate(141.218 9.421 12.25)scale(12.1065 12.6743)" gradientUnits="userSpaceOnUse"><stop class="vkvu1ib_x"/><stop offset="1" class="qmt731a1o"/></radialGradient><radialGradient id="ihI0qJb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.06243 9.06255 -9.18689 -11.2142 15.063 10.813)" gradientUnits="userSpaceOnUse"><stop class="x-3y89bix"/><stop offset=".464" class="vt77mxbnd"/><stop offset=".669" class="pqi30p8km"/><stop offset=".895" class="cxvcljbeh"/></radialGradient><radialGradient id="iK2dGYv" cx="0" cy="0" r="1" gradientTransform="rotate(112.77 3.364 9.581)scale(5.4904 5.50569)" gradientUnits="userSpaceOnUse"><stop class="rx7k7uerl"/><stop offset="1" class="z7mrygimp"/></radialGradient><radialGradient id="i7h8ilN" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.8125 -3.82312 .12536 12.062 10.25)" gradientUnits="userSpaceOnUse"><stop class="txw49acqw"/><stop offset="1" class="ao_uegj5q"/></radialGradient><radialGradient id="ionSY9d" cx="0" cy="0" r="1" gradientTransform="matrix(-2 17.56249 -22.93844 -2.6122 13.875 10)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="gn-qjlbed"/><stop offset=".662" class="k5xgcc44a"/></radialGradient><radialGradient id="ie8kgHe" cx="0" cy="0" r="1" gradientTransform="matrix(25.75003 -4.25 3.63823 22.04338 7.75 14.563)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="qaaw70bph"/><stop offset=".642" class="fw-ioe-bz"/></radialGradient><radialGradient id="i4YxYIe" cx="0" cy="0" r="1" gradientTransform="matrix(.28037 3.8298 -3.56669 .2611 17.617 6.64)" gradientUnits="userSpaceOnUse"><stop class="an1pn6b5d"/><stop offset="1" class="yinrkiq1i"/></radialGradient><radialGradient id="iTRoG5d" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 5.269 5.228)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="iNGoR4d" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 4.45 7.487)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="iRzDtPb" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 3.575 11.123)scale(.70721)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="ivpriqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64844 .42187 -.42187 -.64844 12.7 18.28)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="iHVLxlc" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 -5.3 17.096)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="ipuyAVc" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 2.334 5.078)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="icuPwfe" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 1.148 6.446)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="islRVpg" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 4.915 12.313)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="ihJZXob" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 1.949 15.462)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="ijdBLfc" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 1.2 6.522)scale(.7736)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="isOxcGe" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 -4.544 9.406)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="iqKPffc" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 7.097 10.342)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="iV9xhgj" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 5.02 13.86)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="iZF7Ckb" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 .007 9.986)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="iehlBQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 1.04687 -1.37 -.24537 7.695 16.27)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="i9xdynd" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 7.851 5.825)scale(.7736)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="i82xy0b" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 4.363 14.154)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="iEq0moc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64844 .42187 -.42187 -.64844 11.07 7.21)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="iwprcNc" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 .617 10.57)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="ijyivKf" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 4.875 9.861)scale(.7736)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="iUcE7xo" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 -2.77 16.687)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="i6NOQhs" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 2.005 6.85)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="i4axKhd" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 .247 8.37)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="iH5ZCxe" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 5.247 10.548)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="ip8Q8Hc" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 2.85 13.547)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="iCz9bmb" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 2.293 7.795)scale(.70721)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="iOSjhRb" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 2.359 7.758)scale(.7736)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="iCyC9Kb" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 -4.14 11.93)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="irpr0ow" cx="0" cy="0" r="1" gradientTransform="rotate(146.952 6.977 7.35)scale(.7736)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="yp820flhy"/><stop offset=".605" class="kpy4ejd-u"/></radialGradient><radialGradient id="itLYR4b" cx="0" cy="0" r="1" gradientTransform="rotate(78.852 1.982 15.322)scale(.67723)" gradientUnits="userSpaceOnUse"><stop class="ihmza1i0c"/><stop offset="1" class="d69j9oz-g"/></radialGradient><radialGradient id="iPzNM8b" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 1.772 10.318)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="i28byRd" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 -1.045 12.256)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><radialGradient id="ius4cSZ" cx="0" cy="0" r="1" gradientTransform="rotate(129.268 5.475 7.078)scale(1.4935)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="pi4t44bhb"/><stop offset=".495" class="dyccbhugr"/></radialGradient><radialGradient id="i2nI88b" cx="0" cy="0" r="1" gradientTransform="rotate(100.154 4.137 9.657)scale(1.06353 1.3918)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="g5gyaethh"/><stop offset=".706" class="fc1rvfbkw"/></radialGradient><filter id="iKdZv8b" width="20.111" height="19.953" x="9.42" y="8.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="ii7Gjkb" width="20.111" height="18.925" x="9.42" y="8.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i1SdFVb" width="8.378" height="3.557" x="9.641" y="18.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".375"/></filter><filter id="iiGtsyc" width="1.459" height="1.516" x="11.641" y="3.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iejPN6b" width="1.385" height="1.438" x="16.613" y="15.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i1pvymc" width="1.385" height="1.438" x="18.697" y="10.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i4D1JJc" width="1.393" height="1.63" x="13.503" y="6.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iXxDMvb" width="9.361" height="9.463" x="12.858" y="1.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".5"/></filter><filter id="i9Llqfc" width="1.408" height="1.408" x="11.75" y="17.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iZV7Uqb" width="1.459" height="1.516" x="6.719" y="6.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iu2FLyb" width="1.421" height="1.516" x="7.655" y="9.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iYLurGb" width="1.78" height="1.485" x="4.469" y="10.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="inAJVVy" width="1.459" height="1.516" x="6.696" y="15.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i3GAboc" width="1.408" height="1.408" x="16.619" y="6.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iXHurAG" width="1.323" height="1.469" x="10.101" y="6.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="iRCuV7c" width="1.408" height="1.408" x="13.305" y="15.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="itB72de" width="1.408" height="1.408" x="15.752" y="9.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="inq507b" width="1.459" height="1.317" x="15.654" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i1f2GpY" width="1.459" height="1.516" x="9.9" y="15.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><filter id="i0vwIjO" width="1.408" height="1.408" x="7.579" y="12.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33171" stdDeviation=".125"/></filter><linearGradient id="iBw4GGb" x1="19.553" x2="19.553" y1="7.957" y2="27.411" gradientUnits="userSpaceOnUse"><stop class="gr-8c6bng"/><stop offset=".099" class="y1b1sbcwg"/><stop offset=".185" class="fvcaydb_a"/><stop offset=".246" class="bhows8bzg"/><stop offset=".478" class="j1zc68aac"/><stop offset=".616" class="te_k0nbdw"/><stop offset=".744" class="zq5h55bey"/><stop offset=".821" class="bkzp54mty"/><stop offset=".905" class="ys5iahb1j"/><stop offset="1" class="e8p9_j6nb"/></linearGradient><linearGradient id="iOzGdRd" x1="5.348" x2="4.734" y1="11.516" y2="12.063" gradientUnits="userSpaceOnUse"><stop class="o2--rtbux"/><stop offset="1" class="lqrj_gbxj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bagel" /></template>
<style>
.a4zifxbhr {
  stop-color: var(--svg-color--c59186, #C59186);
}

.an1pn6b5d {
  stop-color: var(--svg-color--ffeda7, #FFEDA7);
}

.ao_uegj5q {
  stop-color: var(--svg-color--e78871, #E78871);
  stop-opacity: 0;
}

.bhows8bzg {
  stop-color: var(--svg-color--fffaf9, #FFFAF9);
}

.bk3c8_nkf {
  fill: var(--svg-color--ffe8e2, #FFE8E2);
  fill-rule: evenodd;
  d: path("M23.82 9.28c-.217-.337-.385-.599-.93-.796c-.764-.277-1.675-.094-2.558.083c-.418.084-.829.166-1.216.199l-1.719-.805c-.805-.04-1.6.219-2.226.726c0 0-.093.922-1.14 1.594a4.8 4.8 0 0 1-1.468.649c-.422.12-.773.219-1.266.68c-.577.537-.592 1.236-.609 1.949c-.01.434-.02.874-.157 1.285l-.974 1.563a3.26 3.26 0 0 0 0 2.335l.88 1.555c.156.428.162.875.168 1.32c.009.632.017 1.26.457 1.82c.45.572.882.736 1.4.933c.403.153.858.326 1.413.724c.331.237.558.564.786.891c.342.492.686.986 1.386 1.187c.76.218 1.253.11 1.86-.025a7.7 7.7 0 0 1 1.421-.21c.478-.02.949.11 1.416.238c.558.154 1.11.307 1.662.2c1.016-.197 2.354-2.005 2.354-2.005c.356-.286.821-.435 1.285-.583c.647-.208 1.293-.415 1.642-.99c.337-.555.47-1.442.581-2.183c.049-.324.093-.62.148-.848c.072-.293.293-.572.537-.879c.38-.477.813-1.022.813-1.793c0-.726-.36-1.277-.714-1.82c-.265-.406-.526-.807-.636-1.274a6.5 6.5 0 0 1-.14-1.156c-.035-.58-.066-1.094-.406-1.578c-.398-.567-1.144-.91-1.838-1.228c-.382-.175-.749-.344-1.032-.538c-.707-.485-.967-.889-1.18-1.22m-4.903 10.908h.954c1.265 0 2.295-1 2.285-2.22c0-1.219-1.02-2.218-2.285-2.218h-.954c-1.256 0-2.285.99-2.285 2.219c0 1.22 1.02 2.218 2.285 2.218");
}

.bkzp54mty {
  stop-color: var(--svg-color--e8a9dd, #E8A9DD);
}

.bmftbqbmc {
  fill: var(--svg-color--9f4d46, #9F4D46);
  d: path("M14.009 16.272a.454.454 0 1 0 0-.909a.454.454 0 0 0 0 .909");
}

.bqwpzsk1s {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M8.425 10.286a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.cb961vf9n {
  d: path("M5.563 12.045a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.cdcfgobfz {
  d: path("M8.365 13.685a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .993");
}

.ceu41zgqi {
  fill: var(--svg-color--db7e5a, #DB7E5A);
  d: path("M19.534 28.44h-.11c-5.216 0-9.45-4.243-9.45-9.45s4.244-9.449 9.45-9.449h.11c5.216 0 9.449 4.243 9.449 9.45s-4.233 9.449-9.45 9.449m-.567-11.377a2.385 2.385 0 0 0 0 4.77H20a2.385 2.385 0 0 0 0-4.77z");
}

.crswi9b3q {
  d: path("M14.138 16.179a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.cxvcljbeh {
  stop-color: var(--svg-color--b17950, #B17950);
}

.d-s162mcz {
  d: path("M7.59 7.137a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d69j9oz-g {
  stop-color: var(--svg-color--4a2568, #4A2568);
  stop-opacity: 0;
}

.dlt1iu2hi {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M19.39 12.099c.244 0 .443-.21.443-.47a.456.456 0 0 0-.443-.468a.456.456 0 0 0-.443.469c0 .259.198.469.443.469");
}

.dyccbhugr {
  stop-color: var(--svg-color--c2a68a, #C2A68A);
}

.e8p9_j6nb {
  stop-color: var(--svg-color--e291d8, #E291D8);
}

.f8u124bzp {
  d: path("M12.499 18.99a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .994");
}

.fc1rvfbkw {
  stop-color: var(--svg-color--f5c7bf, #F5C7BF);
}

.fjciawbop {
  stop-color: var(--svg-color--cd5685, #CD5685);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvcaydb_a {
  stop-color: var(--svg-color--fceeef, #FCEEEF);
  stop-opacity: 0;
}

.fw-ioe-bz {
  stop-color: var(--svg-color--fff0a7, #FFF0A7);
}

.g5gyaethh {
  stop-color: var(--svg-color--d48ea7, #D48EA7);
  stop-opacity: 0;
}

.g5n_9-2kf {
  fill: var(--svg-color--ffd7e2, #FFD7E2);
  d: path("M23.573 9.672c-.209-.32-.37-.567-.893-.754c-.735-.263-1.609-.09-2.457.078c-.401.08-.796.158-1.167.188l-1.65-.762a3.18 3.18 0 0 0-2.138.687s2.237 4.098 1.232 4.735c-.426.27-.773.47-1.078.648c-.64.37-1.094.634-1.703 1.195c-.46.425-1.13-.065-1.716-.494c-.547-.4-1.023-.749-1.19-.252l-.936 1.48a3.05 3.05 0 0 0 0 2.212l.845 1.473c.15.406.156.83.162 1.25c.008.6.016 1.193.439 1.724c.43.542.846.698 1.344.884c.386.145.823.308 1.356.685c.318.225.536.534.755.845c.328.465.658.933 1.33 1.123c.73.207 1.204.104 1.787-.023a7.5 7.5 0 0 1 1.364-.199c.459-.02.911.104 1.36.226c.535.146 1.066.29 1.596.189c.975-.187 2.26-1.9 2.26-1.9c.342-.27.788-.41 1.234-.552c.621-.196 1.241-.392 1.577-.937c.323-.525.45-1.366.557-2.067c.047-.307.09-.588.143-.804c.068-.278.28-.542.515-.832c.364-.453.78-.968.78-1.699c0-.687-.345-1.208-.685-1.724c-.254-.384-.506-.764-.61-1.206c-.094-.395-.115-.757-.136-1.095c-.033-.55-.062-1.036-.389-1.495c-.382-.536-1.099-.86-1.765-1.162c-.367-.167-.719-.326-.99-.51c-.68-.46-.929-.842-1.133-1.155m-4.594 10.537h.964c1.278 0 2.318-.997 2.309-2.214c0-1.216-1.03-2.214-2.309-2.214h-.964c-1.268 0-2.308.988-2.308 2.214c0 1.217 1.03 2.214 2.308 2.214");
}

.g7-w8d-ss {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M14.058 8.277c.233.06.486-.14.565-.446s-.048-.603-.282-.663s-.487.14-.565.447c-.079.306.048.602.281.662");
}

.gf9eyc_lq {
  d: path("M16.632 10.416a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .993");
}

.ggktdrf8w {
  d: path("M8.283 13.729a.454.454 0 1 0 0-.909a.454.454 0 0 0 0 .909");
}

.glwxidbit {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M10.63 16.326c.265 0 .48-.228.48-.508a.494.494 0 0 0-.48-.508a.494.494 0 0 0-.48.508c0 .28.215.508.48.508");
}

.gn-qjlbed {
  stop-color: var(--svg-color--d56872, #D56872);
  stop-opacity: 0;
}

.gr-8c6bng {
  stop-color: var(--svg-color--fde1d6, #FDE1D6);
}

.h1_ce3bdi {
  fill-rule: evenodd;
  d: path("m8.315 2.993l.1-.04c4.69-2.285 10.363-.318 12.639 4.362c2.275 4.69.318 10.364-4.372 12.64l-.1.049c-4.59 2.226-10.125.387-12.49-4.094a3 3 0 0 1-.139-.278c-2.285-4.69-.318-10.354 4.362-12.639m3.776 10.97h1.004a2.4 2.4 0 0 0 2.404-2.405a2.406 2.406 0 0 0-2.404-2.404H12.09a2.407 2.407 0 0 0-2.404 2.404a2.407 2.407 0 0 0 2.404 2.405");
}

.hqyy7cc4w {
  stop-color: var(--svg-color--c49086, #C49086);
}

.ihmza1i0c {
  stop-color: var(--svg-color--4a2567, #4A2567);
}

.iqwotzb2m {
  d: path("M14.267 7.971a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.j1zc68aac {
  stop-color: var(--svg-color--fff8fa, #FFF8FA);
}

.j6fj6ib9k {
  stop-color: var(--svg-color--b85c77, #B85C77);
}

.jaj6zizdf {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M19.444 12.045a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.jqko2-7cm {
  d: path("M10.73 16.129a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.k5xgcc44a {
  stop-color: var(--svg-color--da6f75, #DA6F75);
}

.kpy4ejd-u {
  stop-color: var(--svg-color--37263a, #37263A);
}

.kr30-n81j {
  d: path("M23.573 9.672c-.209-.32-.37-.567-.893-.754c-.735-.263-1.609-.09-2.457.078c-.401.08-.796.158-1.167.188l-1.65-.762a3.18 3.18 0 0 0-2.138.687s2.237 4.098 1.232 4.735c-.426.27-.773.47-1.078.648c-.64.37-1.094.634-1.703 1.195c-.46.425-1.13-.065-1.716-.494c-.547-.4-1.023-.749-1.19-.252l-.936 1.48a3.05 3.05 0 0 0 0 2.212l.845 1.473c.15.406.156.83.162 1.25c.008.6.016 1.193.439 1.724c.43.542.846.698 1.344.884c.386.145.823.308 1.356.685c.318.225.536.534.755.845c.328.465.658.933 1.33 1.123c.73.207 1.204.104 1.787-.023a7.5 7.5 0 0 1 1.364-.199c.459-.02.911.104 1.36.226c.535.146 1.066.29 1.596.189c.975-.187 2.26-1.9 2.26-1.9c.342-.27.788-.41 1.234-.552c.621-.196 1.241-.392 1.577-.937c.323-.525.45-1.366.557-2.067c.047-.307.09-.588.143-.804c.068-.278.28-.542.515-.832c.364-.453.78-.968.78-1.699c0-.687-.345-1.208-.685-1.724c-.254-.384-.506-.764-.61-1.206c-.094-.395-.115-.757-.136-1.095c-.033-.55-.062-1.036-.389-1.495c-.382-.536-1.099-.86-1.765-1.162c-.367-.167-.719-.326-.99-.51c-.68-.46-.929-.842-1.133-1.155m-4.594 10.537h.964c1.278 0 2.318-.997 2.309-2.214c0-1.216-1.03-2.214-2.309-2.214h-.964c-1.268 0-2.308.988-2.308 2.214c0 1.217 1.03 2.214 2.308 2.214");
}

.kz7zanbcd {
  stop-color: var(--svg-color--b76a49, #B76A49);
  stop-opacity: 0;
}

.l16v13b1y {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M14.267 7.971a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.l5xjzmead {
  d: path("M12.454 19.147a.454.454 0 1 0 0-.909a.454.454 0 0 0 0 .909");
}

.lhy0o8buo {
  stop-color: var(--svg-color--c38f86, #C38F86);
  stop-opacity: 0;
}

.lpy1urbik {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M10.73 16.129a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.lqrj_gbxj {
  stop-color: var(--svg-color--af5e4e, #AF5E4E);
  stop-opacity: 0;
}

.ltmziab0x {
  d: path("M28.993 16.954c0 5.216-4.243 8.376-9.45 8.376h-.109c-5.107 0-9.28-2.99-9.45-8.058v2.96c0 .11-.01.21-.01.319c0 5.216 4.244 9.449 9.45 9.449h.11c5.216 0 9.449-4.243 9.449-9.45c0-.109 0-.208-.01-.317h.01v-3.28z");
}

.mncfu1f8v {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M17.306 17c.244 0 .443-.21.443-.469a.456.456 0 0 0-.443-.468a.456.456 0 0 0-.443.468c0 .26.199.469.443.469");
}

.my1djhb1t {
  d: path("M7.59 16.954a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.nclwnzwln {
  fill: var(--svg-color--9f4d46, #9F4D46);
  d: path("M16.456 10.512a.454.454 0 1 0 0-.908a.454.454 0 0 0 0 .908");
}

.nd81gmbsd {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M16.384 13.817c.265 0 .48-.183.48-.409s-.215-.408-.48-.408s-.48.183-.48.409s.215.408.48.408");
}

.nexn4bbdt {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M8.365 10.477c.254 0 .46-.228.46-.508s-.206-.508-.46-.508s-.46.227-.46.508c0 .28.206.508.46.508");
}

.nmv-xubvf {
  d: path("M17.407 16.954a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.nql8ltbxc {
  stop-color: var(--svg-color--da90cc, #DA90CC);
  stop-opacity: 0;
}

.o2--rtbux {
  stop-color: var(--svg-color--af5e4e, #AF5E4E);
}

.ohusp2buq {
  d: path("M8.425 10.286a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.oy1j_vybm {
  fill: var(--svg-color--ffad6f, #FFAD6F);
  fill-rule: evenodd;
  d: path("m8.315 2.993l.1-.04c4.69-2.285 10.363-.318 12.639 4.362c2.275 4.69.318 10.364-4.372 12.64l-.1.049c-4.59 2.226-10.125.387-12.49-4.094a3 3 0 0 1-.139-.278c-2.285-4.69-.318-10.354 4.362-12.639m3.776 10.97h1.004a2.4 2.4 0 0 0 2.404-2.405a2.406 2.406 0 0 0-2.404-2.404H12.09a2.407 2.407 0 0 0-2.404 2.404a2.407 2.407 0 0 0 2.404 2.405");
}

.p-vld3bbr {
  d: path("M5.54 12.051c.35-.14.498-.26.45-.53s-.391-.472-.715-.343s-.598.405-.55.676c.047.27.464.338.815.197");
}

.pi4t44bhb {
  stop-color: var(--svg-color--ffffd2, #FFFFD2);
}

.pqi30p8km {
  stop-color: var(--svg-color--ffaa6e, #FFAA6E);
}

.q2kk8z4gy {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M7.448 7.29c.265 0 .48-.228.48-.509a.494.494 0 0 0-.48-.508a.494.494 0 0 0-.48.508c0 .28.215.508.48.508");
}

.qaaw70bph {
  stop-color: var(--svg-color--ffeda4, #FFEDA4);
  stop-opacity: 0;
}

.qmt731a1o {
  stop-color: var(--svg-color--ffd6e0, #FFD6E0);
}

.rcf9jfa-u {
  stop-color: var(--svg-color--e6a8d0, #E6A8D0);
}

.ruqe6ccbr {
  fill: var(--svg-color--c77691, #C77691);
  fill-rule: evenodd;
  d: path("M10.505 20.278c2.807.336 5.478-.511 6.27-.98l.494.865c-.95.561-3.832 1.473-6.878 1.108z");
}

.rx7k7uerl {
  stop-color: var(--svg-color--cb805a, #CB805A);
}

.s3alhcb7x {
  stop-color: var(--svg-color--b56747, #B56747);
}

.sie_6lv-d {
  fill-rule: evenodd;
  d: path("M19.503 10.352c-.33-4.499-3.797-5.796-5.587-5.665l-.058-1.796c2.069-.06 6.68 2.06 7.36 7.318z");
}

.sog9u6bia {
  stop-color: var(--svg-color--ebbbb0, #EBBBB0);
}

.te_k0nbdw {
  stop-color: var(--svg-color--ffe5f1, #FFE5F1);
}

.tfzk03bbr {
  d: path("M12.499 5.11a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.txw49acqw {
  stop-color: var(--svg-color--de7e6c, #DE7E6C);
}

.u7fvtbbna {
  d: path("M16.582 13.814a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.u7h7ggb1e {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M7.425 17.145c.265 0 .48-.228.48-.508a.494.494 0 0 0-.48-.508a.494.494 0 0 0-.48.508c0 .28.215.508.48.508");
}

.uakpcckis {
  stop-color: var(--svg-color--ba5d76, #BA5D76);
  stop-opacity: 0;
}

.udkxz2b2f {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M7.59 16.954a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.uej01l3sj {
  fill: var(--svg-color--9f4d46, #9F4D46);
  d: path("M17.323 7.235a.454.454 0 1 0 0-.908a.454.454 0 0 0 0 .908");
}

.vi3oveb0y {
  d: path("M17.407 7.137a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.vkvu1ib_x {
  stop-color: var(--svg-color--ffeaf2, #FFEAF2);
}

.vt77mxbnd {
  stop-color: var(--svg-color--ffba77, #FFBA77);
}

.w53opvb2z {
  d: path("M19.444 12.045a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.wibpf9bsc {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M7.59 7.137a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.wmwpc4bob {
  fill: var(--svg-color--9f4d46, #9F4D46);
  d: path("M12.454 19.147a.454.454 0 1 0 0-.909a.454.454 0 0 0 0 .909");
}

.wrawjn1dr {
  fill: var(--svg-color--ffb980, #FFB980);
  d: path("M28.993 16.954c0 5.216-4.243 8.376-9.45 8.376h-.109c-5.107 0-9.28-2.99-9.45-8.058v2.96c0 .11-.01.21-.01.319c0 5.216 4.244 9.449 9.45 9.449h.11c5.216 0 9.449-4.243 9.449-9.45c0-.109 0-.208-.01-.317h.01v-3.28z");
}

.wrbo5hgkv {
  fill: var(--svg-color--9f4d46, #9F4D46);
  d: path("M8.283 13.729a.454.454 0 1 0 0-.909a.454.454 0 0 0 0 .909");
}

.x-3y89bix {
  stop-color: var(--svg-color--ffbd83, #FFBD83);
}

.xbkoqgsls {
  d: path("M10.87 7.921a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.xdm34lb1w {
  d: path("M19.534 28.44h-.11c-5.216 0-9.45-4.243-9.45-9.45s4.244-9.449 9.45-9.449h.11c5.216 0 9.449 4.243 9.449 9.45s-4.233 9.449-9.45 9.449m-.567-11.377a2.385 2.385 0 0 0 0 4.77H20a2.385 2.385 0 0 0 0-4.77z");
}

.xtvew8b3p {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M16.582 13.814a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.xy79f-cvq {
  fill: var(--svg-color--b95561, #B95561);
  d: path("M10.58 8.104c.204.08.45-.061.552-.316c.101-.255.018-.527-.186-.608s-.45.06-.551.316c-.102.255-.019.527.185.608");
}

.y1b1sbcwg {
  stop-color: var(--svg-color--fff8f1, #FFF8F1);
}

.y4zkhtrvy {
  fill: var(--svg-color--cd5850, #CD5850);
  fill-rule: evenodd;
  d: path("M23.573 9.593c-.209-.337-.37-.599-.893-.796c-.735-.277-1.609-.094-2.457.083a10 10 0 0 1-1.167.198l-1.65-.804A3.07 3.07 0 0 0 15.267 9s-.09.923-1.095 1.595a4.5 4.5 0 0 1-1.41.649c-.405.12-.741.219-1.215.68c-.554.537-.569 1.236-.585 1.949c-.01.434-.019.873-.15 1.285l-.936 1.563a3.4 3.4 0 0 0 0 2.335l.845 1.555c.15.428.156.875.162 1.32c.008.632.016 1.26.439 1.82c.43.572.846.736 1.344.933c.386.153.823.326 1.356.724c.318.237.536.564.755.891c.328.491.658.985 1.33 1.187c.73.218 1.204.11 1.787-.025c.376-.086.798-.183 1.364-.21c.459-.021.911.11 1.36.238c.535.154 1.066.307 1.596.2c.975-.197 2.26-2.005 2.26-2.005c.342-.286.788-.435 1.234-.584c.621-.207 1.241-.414 1.577-.99c.323-.554.45-1.44.557-2.182c.047-.324.09-.62.143-.849c.068-.293.28-.571.515-.878c.364-.477.78-1.022.78-1.793c0-.726-.345-1.277-.685-1.82c-.254-.406-.506-.807-.61-1.274c-.094-.417-.115-.8-.136-1.156c-.033-.58-.062-1.094-.389-1.578c-.382-.567-1.099-.91-1.765-1.228c-.367-.176-.719-.344-.99-.538c-.68-.486-.929-.889-1.133-1.22M19.037 20.72h1.003a2.417 2.417 0 0 0 2.405-2.437c0-1.34-1.073-2.438-2.405-2.438h-1.003c-1.322 0-2.405 1.088-2.405 2.438c0 1.34 1.073 2.437 2.405 2.437");
}

.ye0l8g_nn {
  fill: var(--svg-color--bb634c, #BB634C);
  d: path("M12.37 5.258c.265 0 .48-.228.48-.508a.494.494 0 0 0-.48-.508a.494.494 0 0 0-.48.508c0 .28.215.508.48.508");
}

.yinrkiq1i {
  stop-color: var(--svg-color--ffeea8, #FFEEA8);
  stop-opacity: 0;
}

.yp820flhy {
  stop-color: var(--svg-color--5c4f6a, #5C4F6A);
}

.ys5iahb1j {
  stop-color: var(--svg-color--ffd8ed, #FFD8ED);
}

.z-9besbip {
  fill-rule: evenodd;
  d: path("M23.82 9.28c-.217-.337-.385-.599-.93-.796c-.764-.277-1.675-.094-2.558.083c-.418.084-.829.166-1.216.199l-1.719-.805c-.805-.04-1.6.219-2.226.726c0 0-.093.922-1.14 1.594a4.8 4.8 0 0 1-1.468.649c-.422.12-.773.219-1.266.68c-.577.537-.592 1.236-.609 1.949c-.01.434-.02.874-.157 1.285l-.974 1.563a3.26 3.26 0 0 0 0 2.335l.88 1.555c.156.428.162.875.168 1.32c.009.632.017 1.26.457 1.82c.45.572.882.736 1.4.933c.403.153.858.326 1.413.724c.331.237.558.564.786.891c.342.492.686.986 1.386 1.187c.76.218 1.253.11 1.86-.025a7.7 7.7 0 0 1 1.421-.21c.478-.02.949.11 1.416.238c.558.154 1.11.307 1.662.2c1.016-.197 2.354-2.005 2.354-2.005c.356-.286.821-.435 1.285-.583c.647-.208 1.293-.415 1.642-.99c.337-.555.47-1.442.581-2.183c.049-.324.093-.62.148-.848c.072-.293.293-.572.537-.879c.38-.477.813-1.022.813-1.793c0-.726-.36-1.277-.714-1.82c-.265-.406-.526-.807-.636-1.274a6.5 6.5 0 0 1-.14-1.156c-.035-.58-.066-1.094-.406-1.578c-.398-.567-1.144-.91-1.838-1.228c-.382-.175-.749-.344-1.032-.538c-.707-.485-.967-.889-1.18-1.22m-4.903 10.908h.954c1.265 0 2.295-1 2.285-2.22c0-1.219-1.02-2.218-2.285-2.218h-.954c-1.256 0-2.285.99-2.285 2.219c0 1.22 1.02 2.218 2.285 2.218");
}

.z7mrygimp {
  stop-color: var(--svg-color--ce855d, #CE855D);
  stop-opacity: 0;
}

.zeldscc-t {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M12.499 5.11a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.zo9q5bcpb {
  fill: var(--svg-color--fff5d4, #FFF5D4);
  d: path("M17.407 16.954a.497.497 0 1 0 0-.994a.497.497 0 0 0 0 .994");
}

.zq5h55bey {
  stop-color: var(--svg-color--ffedf5, #FFEDF5);
}

.zzaddacea {
  stop-color: var(--svg-color--d55d7d, #D55D7D);
}

</style>
