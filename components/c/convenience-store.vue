<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5xr3JZ)"><path fill="url(#idHn4lG)" class="ykzvep5qx"/></g><g filter="url(#i06yqXc)"><path fill="url(#iu4pbxb)" class="de2c5ibjg"/></g><g filter="url(#iWazo6d)"><path fill="url(#iG6SmEe)" class="g47dxzmyp"/></g><g filter="url(#iioEd0c)"><path fill="url(#it123ec)" class="z44rpiehf"/></g><path fill="url(#ipHFBcb)" class="u8poktbhh"/><path fill="url(#irdbMFc)" class="u8poktbhh"/><path fill="url(#iCHAErb)" class="lq5gf3bta"/><path fill="url(#i0lSw6d)" class="lq5gf3bta"/><path fill="url(#iyUiLQe)" class="y5de0k-4v"/><path fill="url(#iWcu9mb)" class="y5de0k-4v"/><path fill="url(#iiN1Eec)" class="y5de0k-4v"/><path fill="url(#iO93sbc)" class="y5de0k-4v"/><path fill="url(#iJrZsYd)" class="y5de0k-4v"/><g filter="url(#iaGZ5Ec)"><path class="lznt2bbpy"/></g><g filter="url(#iiKROTc)"><path fill="url(#iDyAruG)" class="f2acmjy5q"/></g><g filter="url(#iNzixMT)"><path class="eh1m6f5_r"/><path fill="url(#ijhXhcc)" class="sr0dg8bgs"/><path fill="url(#i9GluHc)" class="sr0dg8bgs"/></g><g filter="url(#ixp42ad)"><path fill="url(#ibNBMqd)" class="jm6w1cc2h"/><path fill="url(#iOxlJsc)" class="jm6w1cc2h"/></g><g filter="url(#iTDVyKc)"><rect fill="url(#iR9931d)" class="fkkhydm8x"/><rect fill="url(#ij0DC5R)" class="fkkhydm8x"/><rect fill="url(#i90p0Jc)" class="fkkhydm8x"/></g><g filter="url(#iMllGQd)"><rect fill="url(#iKFLsRb)" class="ikilqex2c"/><rect fill="url(#irU19Yd)" class="ikilqex2c"/><rect fill="url(#iTZp1cb)" class="ikilqex2c"/></g><g filter="url(#i0YGgNe)"><path stroke="url(#iVreY1c)" class="pvfmxjbdi"/></g><g filter="url(#id3ssze)"><path stroke="url(#i48P9zd)" class="vfvlkwbyp"/></g><g filter="url(#iewACGb)"><path stroke="url(#iPilU2c)" class="pw3s3751d"/></g><g filter="url(#iNGi2lZ)"><path stroke="url(#iiSdGDb)" class="yays29bob"/></g><g filter="url(#iQia3Rc)"><path stroke="url(#iCfvGJc)" class="wecihq_6f"/></g><g filter="url(#iCKTRxc)"><path stroke="url(#iFQicjh)" class="la4wehb0f"/></g><g filter="url(#izjD1Ie)"><path stroke="url(#i9Y5VNu)" class="j-4q1mnke"/></g><g filter="url(#iG0dL3c)"><path stroke="url(#iPYuBlb)" class="sq3rrsb0o"/></g><g filter="url(#i4sbcGb)"><path stroke="url(#ikZDHae)" class="p1hmyebcz"/></g><g filter="url(#iLfd0uc)"><path stroke="url(#iOfyLHc)" class="ox55a0bqr"/></g><defs><linearGradient id="idHn4lG" x1="9.564" x2="24.554" y1="8.097" y2="8.097" gradientUnits="userSpaceOnUse"><stop class="psiv3v50o"/><stop offset="1" class="e3orfzb-b"/></linearGradient><linearGradient id="iu4pbxb" x1="10.831" x2="10.831" y1="4.007" y2="9.003" gradientUnits="userSpaceOnUse"><stop class="ud83rqrzu"/><stop offset="1" class="ts8s8zbua"/></linearGradient><linearGradient id="iG6SmEe" x1="14.995" x2="14.995" y1="4.01" y2="9.018" gradientUnits="userSpaceOnUse"><stop class="ud83rqrzu"/><stop offset="1" class="ts8s8zbua"/></linearGradient><linearGradient id="it123ec" x1="20.994" x2="20.994" y1="4.01" y2="9.017" gradientUnits="userSpaceOnUse"><stop class="ud83rqrzu"/><stop offset="1" class="ts8s8zbua"/></linearGradient><linearGradient id="iyUiLQe" x1="2.995" x2="28.995" y1="24.051" y2="24.051" gradientUnits="userSpaceOnUse"><stop class="fej54pbpc"/><stop offset="1" class="vl2jw_bov"/></linearGradient><linearGradient id="iWcu9mb" x1="2.724" x2="3.557" y1="20.528" y2="20.528" gradientUnits="userSpaceOnUse"><stop class="i_bkbkbyc"/><stop offset="1" class="eqhiw3bid"/></linearGradient><linearGradient id="iiN1Eec" x1="5.126" x2="5.126" y1="15.895" y2="16.535" gradientUnits="userSpaceOnUse"><stop class="i_bkbkbyc"/><stop offset="1" class="eqhiw3bid"/></linearGradient><linearGradient id="iJrZsYd" x1="29.064" x2="28.259" y1="21.55" y2="21.55" gradientUnits="userSpaceOnUse"><stop class="ayjhkqb-l"/><stop offset="1" class="yx1u3jbmk"/></linearGradient><linearGradient id="iDyAruG" x1="9.496" x2="9.496" y1="28.012" y2="18.012" gradientUnits="userSpaceOnUse"><stop class="gy_uv2iii"/><stop offset="1" class="zjfko9bdv"/></linearGradient><linearGradient id="ijhXhcc" x1="16.835" x2="17.739" y1="22.005" y2="22.005" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="i9GluHc" x1="19.615" x2="19.615" y1="24.233" y2="23.396" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="ibNBMqd" x1="6.632" x2="27.007" y1="16.01" y2="16.01" gradientUnits="userSpaceOnUse"><stop class="k0lolqbin"/><stop offset="1" class="y7gg6bcsq"/></linearGradient><linearGradient id="iOxlJsc" x1="30.005" x2="28.679" y1="14.583" y2="14.583" gradientUnits="userSpaceOnUse"><stop class="m7qv_zb3n"/><stop offset="1" class="hlg0k2v5r"/></linearGradient><linearGradient id="iR9931d" x1="7.478" x2="7.478" y1="18.987" y2="26.961" gradientUnits="userSpaceOnUse"><stop class="etg9616xi"/><stop offset="1" class="lu4kqhfuz"/></linearGradient><linearGradient id="ij0DC5R" x1="5.915" x2="6.376" y1="22.974" y2="22.974" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="i90p0Jc" x1="6.846" x2="6.846" y1="27.404" y2="25.741" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="iKFLsRb" x1="11.512" x2="11.512" y1="18.987" y2="26.961" gradientUnits="userSpaceOnUse"><stop class="etg9616xi"/><stop offset="1" class="lu4kqhfuz"/></linearGradient><linearGradient id="irU19Yd" x1="9.95" x2="10.411" y1="22.974" y2="22.974" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="iTZp1cb" x1="10.881" x2="10.881" y1="27.404" y2="25.741" gradientUnits="userSpaceOnUse"><stop class="kwgkqy-7p"/><stop offset="1" class="opzz93bzc"/></linearGradient><linearGradient id="iVreY1c" x1="13.413" x2="13.413" y1="18.349" y2="27.957" gradientUnits="userSpaceOnUse"><stop class="c6ut31b-j"/><stop offset="1" class="e66ohf29k"/></linearGradient><linearGradient id="i48P9zd" x1="14.273" x2="5.839" y1="18.442" y2="18.442" gradientUnits="userSpaceOnUse"><stop class="c6ut31b-j"/><stop offset="1" class="q1waxhovs"/></linearGradient><linearGradient id="iPilU2c" x1="12.252" x2="10.351" y1="4.416" y2="5.707" gradientUnits="userSpaceOnUse"><stop class="f_iwjr0fl"/><stop offset="1" class="q1waxhovs"/></linearGradient><linearGradient id="iiSdGDb" x1="12.489" x2="10.867" y1="8.521" y2="9.909" gradientUnits="userSpaceOnUse"><stop class="cy4b4pbqp"/><stop offset="1" class="gn6f3c1jg"/></linearGradient><linearGradient id="iCfvGJc" x1="15.456" x2="14.79" y1="10.692" y2="3.535" gradientUnits="userSpaceOnUse"><stop class="cy4b4pbqp"/><stop offset="1" class="gn6f3c1jg"/></linearGradient><linearGradient id="iFQicjh" x1="17.21" x2="13.322" y1="7.168" y2="7.199" gradientUnits="userSpaceOnUse"><stop class="cy4b4pbqp"/><stop offset="1" class="gn6f3c1jg"/></linearGradient><linearGradient id="i9Y5VNu" x1="15.661" x2="13.624" y1="4.66" y2="5.567" gradientUnits="userSpaceOnUse"><stop class="f_iwjr0fl"/><stop offset="1" class="q1waxhovs"/></linearGradient><linearGradient id="iPYuBlb" x1="22.57" x2="22.567" y1="8.27" y2="4.645" gradientUnits="userSpaceOnUse"><stop class="oektsp7hc"/><stop offset="1" class="szsr5_bcy"/></linearGradient><linearGradient id="ikZDHae" x1="19.491" x2="19.489" y1="8.27" y2="4.645" gradientUnits="userSpaceOnUse"><stop class="oektsp7hc"/><stop offset="1" class="szsr5_bcy"/></linearGradient><linearGradient id="iOfyLHc" x1="23.259" x2="19.27" y1="6.262" y2="6.294" gradientUnits="userSpaceOnUse"><stop class="iv9ab4btc"/><stop offset="1" class="iv9ab4btc"/></linearGradient><filter id="i5xr3JZ" width="18.61" height="7.31" x="6.695" y="2.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.403922 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.364706 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6533" result="effect2_innerShadow_18_6533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.858824 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_6533" result="effect3_innerShadow_18_6533"/></filter><filter id="i06yqXc" width="3.916" height="5.24" x="8.999" y="3.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iWazo6d" width="4.271" height="5.251" x="12.985" y="3.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iioEd0c" width="4.25" height="5.25" x="18.995" y="3.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iaGZ5Ec" width="9.448" height="10.563" x="4.304" y="17.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".25"/></filter><filter id="iiKROTc" width="9.25" height="10.25" x="4.995" y="18.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.113725 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iNzixMT" width="9.26" height="4.26" x="16.745" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.670588 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="ixp42ad" width="28.41" height="4.21" x="1.995" y="11.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.219608 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iTDVyKc" width="3.217" height="8.174" x="5.769" y="18.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.545098 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="iMllGQd" width="3.217" height="8.174" x="9.804" y="18.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.545098 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6533"/></filter><filter id="i0YGgNe" width=".916" height="9.838" x="13.088" y="18.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="id3ssze" width="8.209" height=".65" x="5.514" y="18.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iewACGb" width="2.903" height="2.826" x="9.46" y="4.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iNGi2lZ" width="3.114" height=".75" x="9.46" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iQia3Rc" width=".75" height="4.641" x="15.148" y="4.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iCKTRxc" width="3.75" height=".75" x="13.148" y="7.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="izjD1Ie" width="2.641" height="3.531" x="13.163" y="4.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iG0dL3c" width=".75" height="4.688" x="22.195" y="4.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="i4sbcGb" width=".75" height="4.688" x="19.116" y="4.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><filter id="iLfd0uc" width="3.828" height=".75" x="19.101" y="6.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6533" stdDeviation=".125"/></filter><radialGradient id="ipHFBcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23759 0 0 -3.019 10.922 12.01)" gradientUnits="userSpaceOnUse"><stop class="fvtqrh_pv"/><stop offset="1" class="rrjeg5bst"/></radialGradient><radialGradient id="irdbMFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.65693 0 0 -1.6366 11.152 12.01)" gradientUnits="userSpaceOnUse"><stop class="qmweg3tna"/><stop offset="1" class="kmhc9od5e"/></radialGradient><radialGradient id="iCHAErb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23759 0 0 -3.019 21.922 12.01)" gradientUnits="userSpaceOnUse"><stop class="fvtqrh_pv"/><stop offset="1" class="rrjeg5bst"/></radialGradient><radialGradient id="i0lSw6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65693 0 0 -1.6366 22.152 12.01)" gradientUnits="userSpaceOnUse"><stop class="qmweg3tna"/><stop offset="1" class="kmhc9od5e"/></radialGradient><radialGradient id="iO93sbc" cx="0" cy="0" r="1" gradientTransform="rotate(39.13 -16.923 4.441)scale(14.2611 19.0195)" gradientUnits="userSpaceOnUse"><stop class="z4b7n04rw"/><stop offset="1" class="su9jkodis"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:convenience-store" /></template>
<style>
.ayjhkqb-l {
  stop-color: var(--svg-color--e0dce2, #E0DCE2);
}

.c6ut31b-j {
  stop-color: var(--svg-color--6f3d6c, #6F3D6C);
}

.cy4b4pbqp {
  stop-color: var(--svg-color--464a7a, #464A7A);
}

.de2c5ibjg {
  d: path("M12.665 8.487c0-.35-.19-.48-.54-.48h-1.39l.81-.83c.32-.31.54-.6.68-.88c.13-.27.2-.55.2-.85c0-.47-.15-.82-.45-1.07s-.74-.37-1.3-.37c-.23 0-.47.03-.7.08s-.45.14-.67.25c-.168.084-.34.289-.3.49q.03.15.12.27c.12.16.35.23.59.11a1.6 1.6 0 0 1 .76-.21c.45 0 .69.24.69.59q0 .21-.12.42c-.08.14-.21.31-.39.5l-1.24 1.32c-.1.1-.17.2-.23.3s-.07.18-.07.31c0 .19.05.33.14.42c.09.1.24.14.44.14h2.44c.407 0 .53-.217.53-.51");
}

.e3orfzb-b {
  stop-color: var(--svg-color--bdb5c2, #BDB5C2);
}

.e66ohf29k {
  stop-color: var(--svg-color--44487c, #44487C);
}

.eh1m6f5_r {
  fill: var(--svg-color--5ee6ff, #5EE6FF);
  d: path("M25.515 24.01h-8.03a.49.49 0 0 1-.49-.49v-3.03c0-.27.22-.49.49-.49h8.03c.27 0 .49.22.49.49v3.03c-.01.27-.23.49-.49.49");
}

.eqhiw3bid {
  stop-color: var(--svg-color--6e616e, #6E616E);
  stop-opacity: 0;
}

.etg9616xi {
  stop-color: var(--svg-color--4dc7ff, #4DC7FF);
}

.f_iwjr0fl {
  stop-color: var(--svg-color--6f436f, #6F436F);
}

.f2acmjy5q {
  d: path("M13.995 28.01h-9V18.6c0-.33.26-.59.59-.59h7.82c.33 0 .59.26.59.59z");
}

.fej54pbpc {
  stop-color: var(--svg-color--a59ca9, #A59CA9);
}

.fkkhydm8x {
  width: 3.017px;
  height: 7.974px;
  x: 5.969px;
  y: 18.987px;
  rx: 0.35px;
}

.ft5dv1b6b {
  fill: none;
}

.fvtqrh_pv {
  stop-color: var(--svg-color--7a5e81, #7A5E81);
}

.g47dxzmyp {
  d: path("M17.005 7.53c-.02.27-.25.47-.52.47h-.5v.49c0 .27-.2.5-.47.52a.496.496 0 0 1-.53-.5V8h-1.51c-.09 0-.17-.03-.25-.07c-.01-.01-.02 0-.03-.01l-.03-.03a.2.2 0 0 1-.07-.07c-.02-.03-.04-.05-.05-.08s-.03-.05-.03-.09a.4.4 0 0 1-.02-.1c0-.02-.01-.03-.01-.05s.01-.03.01-.04c0-.03.01-.07.02-.1s.02-.06.04-.09c.01-.01.01-.03.02-.04l2.01-3l.03-.03c.02-.03.04-.05.07-.07s.05-.04.08-.05c.03-.02.06-.03.09-.04s.06-.02.1-.02c.02 0 .03-.01.05-.01s.03.01.05.01c.03 0 .06.01.09.02s.06.02.09.04c.01.01.03.01.04.02l.03.03c.03.02.05.04.07.07s.04.05.05.08s.03.05.03.09c.01.03.02.07.02.1c0 .02.01.03.01.05v2.5h.51c.3-.02.53.22.51.51M14.995 7v-.85l-.57.85z");
}

.gn6f3c1jg {
  stop-color: var(--svg-color--464a7a, #464A7A);
  stop-opacity: 0;
}

.gy_uv2iii {
  stop-color: var(--svg-color--323870, #323870);
}

.hlg0k2v5r {
  stop-color: var(--svg-color--ff5766, #FF5766);
  stop-opacity: 0;
}

.i_bkbkbyc {
  stop-color: var(--svg-color--6e616e, #6E616E);
}

.ikilqex2c {
  width: 3.017px;
  height: 7.974px;
  x: 10.004px;
  y: 18.987px;
  rx: 0.35px;
}

.iv9ab4btc {
  stop-color: var(--svg-color--4f3465, #4F3465);
}

.j-4q1mnke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.538 7.395l1.89-2.781");
}

.jm6w1cc2h {
  d: path("M29.235 16.01H2.765a.77.77 0 0 1-.77-.77v-2.47c0-.42.34-.77.77-.77h26.47c.42 0 .77.34.77.77v2.47c-.01.43-.35.77-.77.77");
}

.k0lolqbin {
  stop-color: var(--svg-color--ef3d89, #EF3D89);
}

.kmhc9od5e {
  stop-color: var(--svg-color--836488, #836488);
  stop-opacity: 0;
}

.kwgkqy-7p {
  stop-color: var(--svg-color--5dffff, #5DFFFF);
}

.la4wehb0f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.523 7.457h-3");
}

.lq5gf3bta {
  d: path("M21.995 10.01h-1v2h1z");
}

.lu4kqhfuz {
  stop-color: var(--svg-color--62f1ff, #62F1FF);
}

.lznt2bbpy {
  fill: var(--svg-color--695c6f, #695C6F);
  d: path("M13.252 27.832H4.804v-8.998c0-.316.244-.564.554-.564h7.34c.31 0 .554.248.554.564z");
}

.m7qv_zb3n {
  stop-color: var(--svg-color--ff5766, #FF5766);
}

.oektsp7hc {
  stop-color: var(--svg-color--434072, #434072);
}

.opzz93bzc {
  stop-color: var(--svg-color--5dffff, #5DFFFF);
  stop-opacity: 0;
}

.ox55a0bqr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.476 6.551h3.078");
}

.p1hmyebcz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.491 4.489v3.937");
}

.psiv3v50o {
  stop-color: var(--svg-color--a59eaa, #A59EAA);
}

.pvfmxjbdi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.413 18.442c.089.015.266 0 .266.234v8.953");
}

.pw3s3751d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.835 4.535c.245-.062.89-.25 1.422-.093c.64.187 1.156.984.219 2.015");
}

.q1waxhovs {
  stop-color: var(--svg-color--6f3d6c, #6F3D6C);
  stop-opacity: 0;
}

.qmweg3tna {
  stop-color: var(--svg-color--836488, #836488);
}

.rrjeg5bst {
  stop-color: var(--svg-color--281d26, #281D26);
}

.sq3rrsb0o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.57 4.489v3.937");
}

.sr0dg8bgs {
  d: path("M25.515 24.01h-8.03a.49.49 0 0 1-.49-.49v-3.03c0-.27.22-.49.49-.49h8.03c.27 0 .49.22.49.49v3.03c-.01.27-.23.49-.49.49");
}

.su9jkodis {
  stop-color: var(--svg-color--887b8b, #887B8B);
  stop-opacity: 0;
}

.szsr5_bcy {
  stop-color: var(--svg-color--6b3e6c, #6B3E6C);
}

.ts8s8zbua {
  stop-color: var(--svg-color--222058, #222058);
}

.u8poktbhh {
  d: path("M10.995 10.01h-1v2h1z");
}

.ud83rqrzu {
  stop-color: var(--svg-color--5d235a, #5D235A);
}

.vfvlkwbyp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.398 18.442h-7.56");
}

.vl2jw_bov {
  stop-color: var(--svg-color--bfb4c5, #BFB4C5);
}

.wecihq_6f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.523 8.504v-3.89");
}

.y5de0k-4v {
  d: path("M28.995 12.01h-26v16h26z");
}

.y7gg6bcsq {
  stop-color: var(--svg-color--ff3d51, #FF3D51);
}

.yays29bob {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.2 8.504H9.834");
}

.ykzvep5qx {
  d: path("M24.015 10.01H7.985c-.54 0-.99-.44-.99-.99V3.99c0-.54.44-.99.99-.99h16.03c.54 0 .99.44.99.99v5.03c-.01.55-.45.99-.99.99");
}

.yx1u3jbmk {
  stop-color: var(--svg-color--e0dce2, #E0DCE2);
  stop-opacity: 0;
}

.z44rpiehf {
  d: path("M22.995 4.5v4.02c0 .27-.22.49-.49.49h-.02a.49.49 0 0 1-.49-.49v-1.5h-2v1.5c0 .27-.22.49-.49.49h-.02a.49.49 0 0 1-.49-.49V4.5c0-.27.22-.49.49-.49h.02c.27 0 .49.22.49.49v1.51h2V4.5c0-.27.22-.49.49-.49h.02c.27 0 .49.22.49.49");
}

.z4b7n04rw {
  stop-color: var(--svg-color--887b8b, #887B8B);
}

.zjfko9bdv {
  stop-color: var(--svg-color--5c275c, #5C275C);
}

</style>
