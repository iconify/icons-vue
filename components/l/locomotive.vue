<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOQihhd)"><path fill="url(#iraynVd)" class="nhbq3-b2q"/></g><path fill="url(#iVOPhod)" class="g_udg1p-f"/><path fill="url(#iXtthpb)" class="uo49sqbug"/><path fill="url(#iRtJC4b)" class="uo49sqbug"/><path fill="url(#ibUpB8n)" class="yph09wi7m"/><path fill="url(#ierz8wc)" class="yph09wi7m"/><path fill="url(#ibzRbre)" class="yph09wi7m"/><path fill="url(#irK74bb)" class="yph09wi7m"/><path fill="url(#ibUpB8n)" class="bwm0fxgsq"/><path fill="url(#ierz8wc)" class="bwm0fxgsq"/><path fill="url(#ibzRbre)" class="bwm0fxgsq"/><path fill="url(#irK74bb)" class="bwm0fxgsq"/><path fill="url(#iGRwZge)" class="trc2g4bll"/><g filter="url(#i015xwd)"><path fill="url(#iUgqJFb)" class="o3i5ehblj"/></g><g filter="url(#iGuk5Ie)"><path fill="url(#iA8ALwe)" class="an0_zp19m"/><path fill="url(#ic7OrId)" class="an0_zp19m"/></g><path fill="url(#iryeQ4c)" class="an0_zp19m"/><path fill="url(#i1Q2S7d)" class="l3keb9bgp"/><path fill="url(#ia78zfe)" class="l3keb9bgp"/><path fill="url(#iHuk7Pe)" class="l3keb9bgp"/><g filter="url(#iG1eSre)"><path fill="url(#iKNLJod)" class="qomaz_ufv"/></g><g filter="url(#inbj78d)"><path fill="url(#iI46k8b)" class="z8pw-fb-s"/><path fill="url(#izA0FXd)" class="z8pw-fb-s"/></g><path fill="url(#iOpXA6c)" class="az4v_jb4b"/><g filter="url(#ilQ6r6t)"><path fill="url(#iKxbxUb)" class="dul2t4bge"/><path fill="url(#i9QwMwc)" class="dul2t4bge"/><path fill="url(#irhoODX)" class="dul2t4bge"/><path fill="url(#irxa4hc)" class="dul2t4bge"/></g><path fill="url(#imy87Mc)" class="dul2t4bge"/><path fill="url(#ijnqPKc)" class="lb80_4bwj"/><path fill="url(#iU5fA2c)" class="lb80_4bwj"/><g filter="url(#iB9JqOd)"><path fill="url(#idV73Zb)" class="k_qyr8b2j"/></g><g filter="url(#ijV5amb)"><path stroke="url(#iFJyxgY)" class="ixu6ffgzy"/></g><g filter="url(#iBAjf4W)"><path fill="url(#iiIi4he)" class="gks3ygbql"/><path fill="url(#i0a4Nud)" class="gks3ygbql"/><path fill="url(#iiv9uwb)" class="gks3ygbql"/></g><g filter="url(#i4jypec)"><path class="t1s_lofxh"/></g><g filter="url(#iOdcofe)"><path fill="url(#iqe3wTc)" class="n9wbuvbrt"/></g><g filter="url(#ipdRwxd)"><path fill="url(#iJlYhoc)" class="h90gdccet"/><path fill="url(#iNZhLie)" class="h90gdccet"/><path fill="url(#iyBzMTc)" class="h90gdccet"/></g><g filter="url(#igILXjc)"><path class="jr6e6pzup"/></g><g filter="url(#iaOV5mb)"><path stroke="url(#iVmNhxc)" class="p0mncr12a"/></g><path fill="url(#iVN22Xe)" class="gks3ygbql"/><path fill="url(#isBRXYd)" class="h90gdccet"/><g filter="url(#iY0USbb)"><rect fill="url(#iRXDXrd)" class="c_sq6bcok"/><rect fill="url(#itKTTjb)" class="c_sq6bcok"/><rect fill="url(#iOC8Cxe)" class="c_sq6bcok"/></g><g filter="url(#ijtPvce)"><path stroke="url(#ij39Jde)" class="r-jsookux"/></g><g filter="url(#iNeBDhF)"><path stroke="url(#iCWipRd)" class="feuqjvb9c"/></g><g filter="url(#iFAXjNE)"><path stroke="url(#iM8bobb)" class="i6-ikks9u"/></g><defs><linearGradient id="iraynVd" x1="6.497" x2="6.497" y1="17.517" y2="20.49" gradientUnits="userSpaceOnUse"><stop class="dnlsmr62i"/><stop offset="1" class="bandj9srs"/></linearGradient><linearGradient id="iVOPhod" x1="18.497" x2="18.497" y1="23.634" y2="26.319" gradientUnits="userSpaceOnUse"><stop class="eqc-y-y4o"/><stop offset="1" class="l4k2z5y7l"/></linearGradient><linearGradient id="iXtthpb" x1="9" x2="15" y1="13.003" y2="13.003" gradientUnits="userSpaceOnUse"><stop offset=".117" class="zebpwk2-p"/><stop offset=".6" class="hua-e3-oc"/><stop offset=".845" class="hua-e3-oc"/><stop offset="1" class="lyipv4u8g"/></linearGradient><linearGradient id="iRtJC4b" x1="12" x2="12" y1="12" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="srkz0ybtw"/><stop offset="1" class="xxo4ijmuj"/></linearGradient><linearGradient id="ibUpB8n" x1="8.29" x2="16.771" y1="9.503" y2="9.503" gradientUnits="userSpaceOnUse"><stop class="wwplzxbmt"/><stop offset="1" class="wa50ce89b"/></linearGradient><linearGradient id="irK74bb" x1="12" x2="12" y1="12.219" y2="9.483" gradientUnits="userSpaceOnUse"><stop offset=".592" class="w-d2n-b-w"/><stop offset="1" class="wq-atkm-x"/></linearGradient><linearGradient id="iGRwZge" x1="14.998" x2="16.997" y1="16.003" y2="16.003" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="qzooa0bqp"/></linearGradient><linearGradient id="iUgqJFb" x1="14.748" x2="14.748" y1="21.947" y2="15.762" gradientUnits="userSpaceOnUse"><stop class="fl1xmeb3m"/><stop offset="1" class="p43hpsb5w"/></linearGradient><linearGradient id="iA8ALwe" x1="23.997" x2="23.997" y1="6.01" y2="21.833" gradientUnits="userSpaceOnUse"><stop class="xmeuopuew"/><stop offset="1" class="uv-bi6-ug"/></linearGradient><linearGradient id="i1Q2S7d" x1="2.549" x2="8.362" y1="27.594" y2="27.594" gradientUnits="userSpaceOnUse"><stop class="vt64w02at"/><stop offset="1" class="j-hfbzcfi"/></linearGradient><linearGradient id="ia78zfe" x1="3.784" x2="4.712" y1="26" y2="26.921" gradientUnits="userSpaceOnUse"><stop offset=".273" class="rpym8mb2m"/><stop offset="1" class="ati5lcbkt"/></linearGradient><linearGradient id="iHuk7Pe" x1="4.987" x2="4.987" y1="29.226" y2="28.166" gradientUnits="userSpaceOnUse"><stop offset=".316" class="vlm4pjnnw"/><stop offset="1" class="f-p0qvbsd"/></linearGradient><linearGradient id="iKNLJod" x1="15.256" x2="15.256" y1="28.704" y2="25" gradientUnits="userSpaceOnUse"><stop class="eon5ac39u"/><stop offset="1" class="m73r_rj4j"/></linearGradient><linearGradient id="iI46k8b" x1="11.085" x2="11.085" y1="29" y2="25" gradientUnits="userSpaceOnUse"><stop class="ytw6hxb6m"/><stop offset="1" class="m73r_rj4j"/></linearGradient><linearGradient id="iOpXA6c" x1="6" x2="29" y1="24" y2="24" gradientUnits="userSpaceOnUse"><stop class="m3xqbq_8n"/><stop offset=".093" class="k3g5lvb1a"/><stop offset=".932" class="s48urbclg"/><stop offset="1" class="jthh3ebwk"/></linearGradient><linearGradient id="iKxbxUb" x1="13.174" x2="13.174" y1="26" y2="28" gradientUnits="userSpaceOnUse"><stop class="hb971obhr"/><stop offset="1" class="qnjb9nbml"/></linearGradient><linearGradient id="irxa4hc" x1="13" x2="13" y1="28.359" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="rbeoxglje"/><stop offset="1" class="qldafmbqp"/></linearGradient><linearGradient id="ijnqPKc" x1="7.544" x2="17.128" y1="7.003" y2="7.003" gradientUnits="userSpaceOnUse"><stop class="crrcj3i2g"/><stop offset=".501" class="xpt-1vbgx"/><stop offset=".738" class="e7tiq4b9r"/><stop offset=".942" class="e7tiq4b9r"/><stop offset="1" class="aferqgfbk"/></linearGradient><linearGradient id="idV73Zb" x1="21.384" x2="21.384" y1="28.556" y2="23" gradientUnits="userSpaceOnUse"><stop class="wj5jabb2f"/><stop offset="1" class="m73r_rj4j"/></linearGradient><linearGradient id="iFJyxgY" x1="22.713" x2="20.142" y1="23.59" y2="28.037" gradientUnits="userSpaceOnUse"><stop class="k32fcbjcu"/><stop offset="1" class="ow3an4b8l"/></linearGradient><linearGradient id="iqe3wTc" x1="27.384" x2="27.384" y1="28.556" y2="23" gradientUnits="userSpaceOnUse"><stop class="wj5jabb2f"/><stop offset="1" class="m73r_rj4j"/></linearGradient><linearGradient id="iVmNhxc" x1="28.713" x2="26.142" y1="23.59" y2="28.037" gradientUnits="userSpaceOnUse"><stop class="k32fcbjcu"/><stop offset="1" class="ow3an4b8l"/></linearGradient><linearGradient id="iRXDXrd" x1="27" x2="21.08" y1="7.781" y2="14.076" gradientUnits="userSpaceOnUse"><stop class="toqoaebuh"/><stop offset="1" class="g1bgztb0m"/></linearGradient><linearGradient id="itKTTjb" x1="20.737" x2="22.205" y1="12.438" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="hxkerebas"/><stop offset="1" class="ryrebue7x"/></linearGradient><linearGradient id="iOC8Cxe" x1="23.799" x2="23.799" y1="7.438" y2="11.053" gradientUnits="userSpaceOnUse"><stop class="m8lgtccsc"/><stop offset="1" class="idrh_zb2r"/></linearGradient><linearGradient id="ij39Jde" x1="9.079" x2="21.278" y1="16.41" y2="16.41" gradientUnits="userSpaceOnUse"><stop class="f9rndr6tf"/><stop offset="1" class="psd5utbfl"/></linearGradient><linearGradient id="iCWipRd" x1="9.989" x2="16.662" y1="4.752" y2="4.752" gradientUnits="userSpaceOnUse"><stop class="jm61hacbp"/><stop offset="1" class="qdxs4gb7g"/></linearGradient><linearGradient id="iM8bobb" x1="19.79" x2="29.35" y1="15.029" y2="10.529" gradientUnits="userSpaceOnUse"><stop class="ue55l8_oo"/><stop offset="1" class="kx8wz6azx"/></linearGradient><radialGradient id="ierz8wc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19642 0 0 -4.65125 17.656 9.774)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="pyc--qb6t"/><stop offset="1" class="etf2webwq"/></radialGradient><radialGradient id="ibzRbre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.23289 2.65918 0 14.34 7.5)" gradientUnits="userSpaceOnUse"><stop class="i-15iubhh"/><stop offset="1" class="mmslkdbfy"/></radialGradient><radialGradient id="ic7OrId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.77074 1.82344 -.99056 -.96193 29 6.21)" gradientUnits="userSpaceOnUse"><stop class="oeue1jhnj"/><stop offset="1" class="ed0plvvlp"/></radialGradient><radialGradient id="iryeQ4c" cx="0" cy="0" r="1" gradientTransform="rotate(-35.149 41.262 -19.4)scale(4.96699 12.4225)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="al-twcbig"/><stop offset="1" class="aufnibc-m"/></radialGradient><radialGradient id="izA0FXd" cx="0" cy="0" r="1" gradientTransform="rotate(90.813 -7.878 18.955)scale(1.10167)" gradientUnits="userSpaceOnUse"><stop offset=".807" class="svk4g7ekz"/><stop offset="1" class="nhpptdb4t"/></radialGradient><radialGradient id="i9QwMwc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.90625 0 0 -3.81111 15.55 27)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="o19izcckh"/><stop offset="1" class="d4qfpcbrk"/></radialGradient><radialGradient id="irhoODX" cx="0" cy="0" r="1" gradientTransform="rotate(155.833 5.16 14.978)scale(1.145 1.10706)" gradientUnits="userSpaceOnUse"><stop class="qrck5mxul"/><stop offset="1" class="f7jt0_b9k"/></radialGradient><radialGradient id="imy87Mc" cx="0" cy="0" r="1" gradientTransform="rotate(142.321 4.064 15.42)scale(4.6818 3.58383)" gradientUnits="userSpaceOnUse"><stop class="ve14-zmni"/><stop offset="1" class="fees6-bdc"/></radialGradient><radialGradient id="iU5fA2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16037 0 0 -1.39681 17.325 8)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="wud1aibrx"/><stop offset="1" class="zl4b51beh"/></radialGradient><radialGradient id="iiIi4he" cx="0" cy="0" r="1" gradientTransform="rotate(120.433 3.614 18.721)scale(3.37735)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="i87myzbbk"/><stop offset="1" class="cbcli92ea"/></radialGradient><radialGradient id="i0a4Nud" cx="0" cy="0" r="1" gradientTransform="matrix(3.00633 -2.28934 2.38519 3.1322 19.837 27.038)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="f1royzb0n"/><stop offset="1" class="rfqaujbua"/></radialGradient><radialGradient id="iiv9uwb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.731 16.107 9.089)scale(3.93651)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="cdta95b9o"/><stop offset="1" class="uv76yiy1l"/></radialGradient><radialGradient id="iJlYhoc" cx="0" cy="0" r="1" gradientTransform="rotate(120.433 6.614 20.438)scale(3.37735)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="i87myzbbk"/><stop offset="1" class="cbcli92ea"/></radialGradient><radialGradient id="iNZhLie" cx="0" cy="0" r="1" gradientTransform="matrix(3.00633 -2.28934 2.38519 3.1322 25.837 27.038)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="f1royzb0n"/><stop offset="1" class="rfqaujbua"/></radialGradient><radialGradient id="iyBzMTc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.731 19.107 7.929)scale(3.93651)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="cdta95b9o"/><stop offset="1" class="uv76yiy1l"/></radialGradient><radialGradient id="iVN22Xe" cx="0" cy="0" r="1" gradientTransform="rotate(127.161 5.538 17.714)scale(4.04845)" gradientUnits="userSpaceOnUse"><stop class="ve14-zmni"/><stop offset="1" class="fees6-bdc"/></radialGradient><radialGradient id="isBRXYd" cx="0" cy="0" r="1" gradientTransform="rotate(127.161 8.538 19.204)scale(4.04845)" gradientUnits="userSpaceOnUse"><stop class="ve14-zmni"/><stop offset="1" class="fees6-bdc"/></radialGradient><filter id="iOQihhd" width="3" height="3" x="5" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.533333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="i015xwd" width="18.75" height="10" x="6" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.156863 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="iGuk5Ie" width="11" height="17.99" x="19" y="6.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.172549 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="iG1eSre" width="4" height="4" x="13" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="inbj78d" width="4" height="4" x="8.828" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="ilQ6r6t" width="6" height="2.1" x="10" y="26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.478431 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="iB9JqOd" width="6" height="6" x="18" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="ijV5amb" width="6.148" height="6.148" x="17.926" y="22.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".2"/></filter><filter id="iBAjf4W" width="4.4" height="4.4" x="18.7" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.137255 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_9008"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_9008" result="shape"/></filter><filter id="i4jypec" width="4.332" height="4.332" x="18.834" y="23.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".375"/></filter><filter id="iOdcofe" width="6" height="6" x="24" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="ipdRwxd" width="4.4" height="4.4" x="24.7" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.137255 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_9008"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_9008" result="shape"/></filter><filter id="igILXjc" width="4.332" height="4.332" x="24.834" y="23.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".375"/></filter><filter id="iaOV5mb" width="6.148" height="6.148" x="23.926" y="22.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".2"/></filter><filter id="iY0USbb" width="6.544" height="6.544" x="20.456" y="8.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.490196 0 0 0 0 0.870588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9008"/></filter><filter id="ijtPvce" width="12.412" height="3" x="7.3" y="13.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".5"/></filter><filter id="iNeBDhF" width="8.95" height="1.2" x="7.732" y="3.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".2"/></filter><filter id="iFAXjNE" width="9.404" height="16.366" x="19.8" y="5.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9008" stdDeviation=".4"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:locomotive" /></template>
<style>
.aferqgfbk {
  stop-color: var(--svg-color--f6b253, #F6B253);
}

.al-twcbig {
  stop-color: var(--svg-color--e53352, #E53352);
}

.an0_zp19m {
  d: path("M29 24H19V7.76c0-.97.78-1.75 1.75-1.75h6.49c.97 0 1.75.78 1.75 1.75V24z");
}

.ati5lcbkt {
  stop-color: var(--svg-color--9c4150, #9C4150);
  stop-opacity: 0;
}

.aufnibc-m {
  stop-color: var(--svg-color--e53352, #E53352);
  stop-opacity: 0;
}

.az4v_jb4b {
  d: path("M29 22H6v2h23z");
}

.bandj9srs {
  stop-color: var(--svg-color--b6702e, #B6702E);
}

.bwm0fxgsq {
  d: path("M7 9.41V7h10v2.41c0 .38-.15.74-.42 1.01L15 12H9l-1.58-1.58C7.15 10.15 7 9.79 7 9.41");
}

.c_sq6bcok {
  width: 6.044px;
  height: 6.044px;
  x: 20.956px;
  y: 8.031px;
  rx: 1px;
}

.cbcli92ea {
  stop-color: var(--svg-color--8e6d9c, #8E6D9C);
}

.cdta95b9o {
  stop-color: var(--svg-color--6e656e, #6E656E);
  stop-opacity: 0;
}

.crrcj3i2g {
  stop-color: var(--svg-color--a2693c, #A2693C);
}

.d4qfpcbrk {
  stop-color: var(--svg-color--664356, #664356);
}

.dnlsmr62i {
  stop-color: var(--svg-color--e29a24, #E29A24);
}

.dul2t4bge {
  d: path("M15 26h-4c-.55 0-1 .45-1 1s.45 1 1 1h4c.55 0 1-.45 1-1s-.45-1-1-1");
}

.e7tiq4b9r {
  stop-color: var(--svg-color--ffc651, #FFC651);
}

.ed0plvvlp {
  stop-color: var(--svg-color--f2508e, #F2508E);
  stop-opacity: 0;
}

.eon5ac39u {
  stop-color: var(--svg-color--413649, #413649);
}

.eqc-y-y4o {
  stop-color: var(--svg-color--231928, #231928);
}

.etf2webwq {
  stop-color: var(--svg-color--42203e, #42203E);
  stop-opacity: 0;
}

.f-p0qvbsd {
  stop-color: var(--svg-color--a52c66, #A52C66);
  stop-opacity: 0;
}

.f1royzb0n {
  stop-color: var(--svg-color--f4e9e4, #F4E9E4);
  stop-opacity: 0;
}

.f7jt0_b9k {
  stop-color: var(--svg-color--d8cacc, #D8CACC);
  stop-opacity: 0;
}

.f9rndr6tf {
  stop-color: var(--svg-color--695579, #695579);
}

.fees6-bdc {
  stop-color: var(--svg-color--efe3dd, #EFE3DD);
  stop-opacity: 0;
}

.feuqjvb9c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.332 3.723h7.75");
}

.fl1xmeb3m {
  stop-color: var(--svg-color--3e3842, #3E3842);
}

.ft5dv1b6b {
  fill: none;
}

.g_udg1p-f {
  d: path("M29 28H8v-4h21z");
}

.g1bgztb0m {
  stop-color: var(--svg-color--55e4ff, #55E4FF);
}

.gks3ygbql {
  d: path("M21 28a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.h90gdccet {
  d: path("M27 28a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.hb971obhr {
  stop-color: var(--svg-color--b7abb2, #B7ABB2);
}

.hua-e3-oc {
  stop-color: var(--svg-color--52455c, #52455C);
}

.hxkerebas {
  stop-color: var(--svg-color--57faff, #57FAFF);
}

.i-15iubhh {
  stop-color: var(--svg-color--685575, #685575);
}

.i6-ikks9u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M21 7h6.004a1 1 0 0 1 1 1v12.966");
}

.i87myzbbk {
  stop-color: var(--svg-color--b8a6b6, #B8A6B6);
}

.idrh_zb2r {
  stop-color: var(--svg-color--1c89ea, #1C89EA);
  stop-opacity: 0;
}

.ixu6ffgzy {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.549 26a2.549 2.549 0 1 1-5.098 0a2.549 2.549 0 0 1 5.098 0Z");
}

.j-hfbzcfi {
  stop-color: var(--svg-color--eb344a, #EB344A);
}

.jm61hacbp {
  stop-color: var(--svg-color--827091, #827091);
  stop-opacity: 0;
}

.jr6e6pzup {
  fill: var(--svg-color--b8a7b6, #B8A7B6);
  d: path("M27 27.416a1.416 1.416 0 1 0 0-2.832a1.416 1.416 0 0 0 0 2.832");
}

.jthh3ebwk {
  stop-color: var(--svg-color--f3e8e2, #F3E8E2);
}

.k_qyr8b2j {
  d: path("M21 29a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.k32fcbjcu {
  stop-color: var(--svg-color--7a6788, #7A6788);
}

.k3g5lvb1a {
  stop-color: var(--svg-color--a99aaa, #A99AAA);
}

.kx8wz6azx {
  stop-color: var(--svg-color--ea4b89, #EA4B89);
}

.l3keb9bgp {
  d: path("M2.7 29H8v-5l-1-1l-4.81 4.76A.724.724 0 0 0 2.7 29");
}

.l4k2z5y7l {
  stop-color: var(--svg-color--353037, #353037);
}

.lb80_4bwj {
  d: path("M17 6H7v2h10z");
}

.lyipv4u8g {
  stop-color: var(--svg-color--3d273b, #3D273B);
}

.m3xqbq_8n {
  stop-color: var(--svg-color--706671, #706671);
}

.m73r_rj4j {
  stop-color: var(--svg-color--644d74, #644D74);
}

.m8lgtccsc {
  stop-color: var(--svg-color--1c89ea, #1C89EA);
}

.mmslkdbfy {
  stop-color: var(--svg-color--685575, #685575);
  stop-opacity: 0;
}

.n9wbuvbrt {
  d: path("M27 29a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.nhbq3-b2q {
  d: path("M6.5 20a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.nhpptdb4t {
  stop-color: var(--svg-color--342340, #342340);
  stop-opacity: 0;
}

.o19izcckh {
  stop-color: var(--svg-color--664356, #664356);
  stop-opacity: 0;
}

.o3i5ehblj {
  d: path("M23.5 24H7.78C6.8 24 6 23.2 6 22.22v-5.47C6 15.23 7.23 14 8.75 14H23.5z");
}

.oeue1jhnj {
  stop-color: var(--svg-color--f2508e, #F2508E);
}

.ow3an4b8l {
  stop-color: var(--svg-color--7a6788, #7A6788);
  stop-opacity: 0;
}

.p0mncr12a {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M29.549 26a2.549 2.549 0 1 1-5.098 0a2.549 2.549 0 0 1 5.098 0Z");
}

.p43hpsb5w {
  stop-color: var(--svg-color--5d4a6d, #5D4A6D);
}

.psd5utbfl {
  stop-color: var(--svg-color--644f7c, #644F7C);
  stop-opacity: 0;
}

.pyc--qb6t {
  stop-color: var(--svg-color--42203e, #42203E);
}

.qdxs4gb7g {
  stop-color: var(--svg-color--827091, #827091);
}

.qldafmbqp {
  stop-color: var(--svg-color--8e689f, #8E689F);
  stop-opacity: 0;
}

.qnjb9nbml {
  stop-color: var(--svg-color--b19db2, #B19DB2);
}

.qomaz_ufv {
  d: path("M15 29a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.qrck5mxul {
  stop-color: var(--svg-color--d8cacc, #D8CACC);
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r-jsookux {
  stroke-linecap: square;
  d: path("M8.8 15.386h9.412");
}

.rbeoxglje {
  stop-color: var(--svg-color--8e689f, #8E689F);
}

.rfqaujbua {
  stop-color: var(--svg-color--f4e9e4, #F4E9E4);
}

.rpym8mb2m {
  stop-color: var(--svg-color--9c4150, #9C4150);
}

.ryrebue7x {
  stop-color: var(--svg-color--57faff, #57FAFF);
  stop-opacity: 0;
}

.s48urbclg {
  stop-color: var(--svg-color--c9b9c1, #C9B9C1);
}

.srkz0ybtw {
  stop-color: var(--svg-color--32203e, #32203E);
}

.svk4g7ekz {
  stop-color: var(--svg-color--342340, #342340);
}

.t1s_lofxh {
  fill: var(--svg-color--b8a7b6, #B8A7B6);
  d: path("M21 27.416a1.416 1.416 0 1 0 0-2.832a1.416 1.416 0 0 0 0 2.832");
}

.toqoaebuh {
  stop-color: var(--svg-color--44aff5, #44AFF5);
}

.trc2g4bll {
  d: path("M16 17c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1c0 .56-.45 1-1 1");
}

.ue55l8_oo {
  stop-color: var(--svg-color--df4f8a, #DF4F8A);
  stop-opacity: 0;
}

.uo49sqbug {
  d: path("M15 12H9v2h6z");
}

.uv-bi6-ug {
  stop-color: var(--svg-color--e73450, #E73450);
}

.uv76yiy1l {
  stop-color: var(--svg-color--6e656e, #6E656E);
}

.ve14-zmni {
  stop-color: var(--svg-color--efe3dd, #EFE3DD);
}

.vlm4pjnnw {
  stop-color: var(--svg-color--a52c66, #A52C66);
}

.vt64w02at {
  stop-color: var(--svg-color--df346a, #DF346A);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w-d2n-b-w {
  stop-color: var(--svg-color--31203d, #31203D);
}

.wa50ce89b {
  stop-color: var(--svg-color--7d6488, #7D6488);
}

.wj5jabb2f {
  stop-color: var(--svg-color--2f1c3b, #2F1C3B);
}

.wq-atkm-x {
  stop-color: var(--svg-color--31203d, #31203D);
  stop-opacity: 0;
}

.wud1aibrx {
  stop-color: var(--svg-color--c0813e, #C0813E);
}

.wwplzxbmt {
  stop-color: var(--svg-color--2e2635, #2E2635);
}

.xmeuopuew {
  stop-color: var(--svg-color--d53779, #D53779);
}

.xpt-1vbgx {
  stop-color: var(--svg-color--faa845, #FAA845);
}

.xxo4ijmuj {
  stop-color: var(--svg-color--32203e, #32203E);
  stop-opacity: 0;
}

.yph09wi7m {
  d: path("M7 6h10V4c0-.55-.45-1-1-1H8c-.55 0-1 .45-1 1z");
}

.ytw6hxb6m {
  stop-color: var(--svg-color--45394f, #45394F);
}

.z8pw-fb-s {
  d: path("M10.828 29a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.zebpwk2-p {
  stop-color: var(--svg-color--312d34, #312D34);
}

.zl4b51beh {
  stop-color: var(--svg-color--c0813e, #C0813E);
  stop-opacity: 0;
}

</style>
