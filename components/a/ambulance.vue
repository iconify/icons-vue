<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihxcN1c)"><path fill="url(#impqCLe)" class="ml7lyl_zv"/></g><g filter="url(#iIysgHd)"><path fill="url(#if7YzNb)" class="xkpht0bnp"/></g><path fill="url(#iEZZKab)" class="xkpht0bnp"/><g filter="url(#ikaKI8b)"><path fill="url(#iiLuTld)" class="k2waddo4y"/></g><path fill="url(#ijc7Cec)" class="k2waddo4y"/><path fill="url(#i8h7Ugd)" class="k2waddo4y"/><path fill="url(#irsM9Rc)" class="k2waddo4y"/><path fill="url(#iMcWtrd)" class="k2waddo4y"/><path fill="url(#ifaRLRc)" class="k2waddo4y"/><path fill="url(#iIIEpRd)" class="k2waddo4y"/><g filter="url(#iyTnZQm)"><path fill="url(#iELltsd)" class="vyc5y4bml"/></g><g filter="url(#ifJ4PJd)"><path fill="url(#iZKc3yM)" class="azm-e0-sg"/><path fill="url(#iPP80Hd)" class="azm-e0-sg"/></g><g filter="url(#ip79uRb)"><path clip-rule="evenodd" class="fqh2grrds"/></g><path fill="url(#ioC5yIe)" class="cxoyg5b7k"/><path fill="url(#ifgmGfc)" class="cxoyg5b7k"/><path fill="url(#iy88Lfb)" class="xk9_g7bcy"/><g filter="url(#iszdnhc)"><path fill="url(#iZLLXjx)" class="cspwcz85c"/><path fill="url(#iTx3RHd)" class="cspwcz85c"/></g><path fill="url(#iGN40wm)" class="x4dz_ej9d"/><path fill="url(#iE1cFQd)" class="p9vhezbkz"/><path fill="url(#inbMuib)" class="p9vhezbkz"/><path fill="url(#i83FKKE)" class="p9vhezbkz"/><path fill="url(#iBmPZfe)" clip-rule="evenodd" class="c8g3lnome"/><path fill="url(#izADzKe)" clip-rule="evenodd" class="c8g3lnome"/><path fill="url(#iZwpSyd)" clip-rule="evenodd" class="c8g3lnome"/><path fill="url(#iPcFKkc)" clip-rule="evenodd" class="c8g3lnome"/><g filter="url(#iwc0Qrq)"><ellipse fill="url(#ivRZWEe)" transform="rotate(38.286 5.996 25.132)" class="k766edczz"/></g><g filter="url(#iioDCXb)"><path fill="url(#iy0Ty3d)" class="ay3u33bqk"/></g><g filter="url(#iXeEhLe)"><path fill="url(#i7LwsdU)" class="cc2x5bbfu"/><path fill="url(#iDxhIib)" class="cc2x5bbfu"/></g><defs><linearGradient id="impqCLe" x1="14.875" x2="28.938" y1="18.245" y2="18.245" gradientUnits="userSpaceOnUse"><stop class="htw3prbeg"/><stop offset=".622" class="nfddcrbxt"/><stop offset="1" class="m8iymzb7n"/></linearGradient><linearGradient id="if7YzNb" x1="15.375" x2="30" y1="26.057" y2="26.057" gradientUnits="userSpaceOnUse"><stop class="n2u2qnb8w"/><stop offset="1" class="uuxicacep"/></linearGradient><linearGradient id="iiLuTld" x1="4" x2="14" y1="25.932" y2="15.12" gradientUnits="userSpaceOnUse"><stop class="yzqbqq6pb"/><stop offset="1" class="zqg4l48wi"/></linearGradient><linearGradient id="ijc7Cec" x1="8" x2="8" y1="11.748" y2="13.427" gradientUnits="userSpaceOnUse"><stop class="suif1cfgx"/><stop offset="1" class="uggp-ibpr"/></linearGradient><linearGradient id="irsM9Rc" x1="14.281" x2="13.559" y1="22.403" y2="22.403" gradientUnits="userSpaceOnUse"><stop class="ijonss59a"/><stop offset="1" class="hrbd7lbfs"/></linearGradient><linearGradient id="iELltsd" x1="25.113" x2="22.973" y1="25.488" y2="30.219" gradientUnits="userSpaceOnUse"><stop class="s_76kmb8c"/><stop offset="1" class="y1ui8gonf"/></linearGradient><linearGradient id="ioC5yIe" x1="28" x2="30.344" y1="23.557" y2="23.557" gradientUnits="userSpaceOnUse"><stop class="y5jx_obwk"/><stop offset="1" class="a0zxqubch"/></linearGradient><linearGradient id="iy88Lfb" x1="2" x2="4" y1="23.401" y2="23.401" gradientUnits="userSpaceOnUse"><stop class="fankhfe2q"/><stop offset="1" class="a8eqjq9ip"/></linearGradient><linearGradient id="iZLLXjx" x1="16.478" x2="10.197" y1="11.835" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="a74tmo3pm"/><stop offset="1" class="zwt_fzbmr"/></linearGradient><linearGradient id="iTx3RHd" x1="3.377" x2="6.27" y1="17.591" y2="17.591" gradientUnits="userSpaceOnUse"><stop class="cq5_47bhh"/><stop offset="1" class="mxulxgbas"/></linearGradient><linearGradient id="iGN40wm" x1="11.402" x2="12.723" y1="10.964" y2="10.964" gradientUnits="userSpaceOnUse"><stop class="r7n0tbc-y"/><stop offset="1" class="fz6lhb-rg"/></linearGradient><linearGradient id="inbMuib" x1="10" x2="11.308" y1="12.057" y2="12.057" gradientUnits="userSpaceOnUse"><stop class="jj7zhpb2o"/><stop offset="1" class="y-dcc-qsz"/></linearGradient><linearGradient id="i83FKKE" x1="13.819" x2="12.745" y1="12.057" y2="12.057" gradientUnits="userSpaceOnUse"><stop class="z37t2t5qb"/><stop offset="1" class="audz23byx"/></linearGradient><linearGradient id="iBmPZfe" x1="22.106" x2="22.106" y1="7.901" y2="9.174" gradientUnits="userSpaceOnUse"><stop class="salz2dthk"/><stop offset="1" class="ovjl_3bnl"/></linearGradient><linearGradient id="izADzKe" x1="22.106" x2="22.106" y1="8.057" y2="8.401" gradientUnits="userSpaceOnUse"><stop class="fwdradjhp"/><stop offset="1" class="q2lci-pbk"/></linearGradient><linearGradient id="iZwpSyd" x1="14.903" x2="17.094" y1="8.314" y2="9.174" gradientUnits="userSpaceOnUse"><stop class="kdjuolb5h"/><stop offset="1" class="xs8ggnbvp"/></linearGradient><linearGradient id="iPcFKkc" x1="30.006" x2="27.78" y1="9.174" y2="9.174" gradientUnits="userSpaceOnUse"><stop class="wtjy1wbrs"/><stop offset="1" class="pm0enebiz"/></linearGradient><linearGradient id="ivRZWEe" x1="6.009" x2="6.002" y1="24.286" y2="26.957" gradientUnits="userSpaceOnUse"><stop offset=".404" class="k7pff3lfr"/><stop offset="1" class="qkog218op"/></linearGradient><linearGradient id="iy0Ty3d" x1="10.134" x2="7.993" y1="25.316" y2="30.047" gradientUnits="userSpaceOnUse"><stop class="s_76kmb8c"/><stop offset="1" class="y1ui8gonf"/></linearGradient><radialGradient id="iEZZKab" cx="0" cy="0" r="1" gradientTransform="matrix(3.0578 -2.8279 .54519 .58952 12.985 28.047)" gradientUnits="userSpaceOnUse"><stop class="tzq4t5bol"/><stop offset="1" class="qcgjw9paw"/></radialGradient><radialGradient id="i8h7Ugd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 1.375 -.28663 -.26383 14 12.198)" gradientUnits="userSpaceOnUse"><stop class="n2r4awbge"/><stop offset="1" class="uhs84-bmt"/></radialGradient><radialGradient id="iMcWtrd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.978 11.976 11.247)scale(3.82796 1.05773)" gradientUnits="userSpaceOnUse"><stop class="fazwaxb2r"/><stop offset="1" class="ih1stibpr"/></radialGradient><radialGradient id="ifaRLRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56248 -2.71875 3.72729 -.77114 5.469 27.838)" gradientUnits="userSpaceOnUse"><stop class="fazwaxb2r"/><stop offset="1" class="ih1stibpr"/></radialGradient><radialGradient id="iIIEpRd" cx="0" cy="0" r="1" gradientTransform="rotate(133.847 -1.094 14.743)scale(3.29313 3.66564)" gradientUnits="userSpaceOnUse"><stop offset=".605" class="gh88s7sup"/><stop offset="1" class="vx3l9nuzv"/></radialGradient><radialGradient id="iZKc3yM" cx="0" cy="0" r="1" gradientTransform="rotate(133.21 6.47 18.402)scale(1.76276 1.52752)" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="je7vqqg0r"/></radialGradient><radialGradient id="iPP80Hd" cx="0" cy="0" r="1" gradientTransform="rotate(-74.924 30.1 -1.227)scale(1.56984 3.21504)" gradientUnits="userSpaceOnUse"><stop class="fdomx0bpj"/><stop offset="1" class="li9m4eegn"/></radialGradient><radialGradient id="ifgmGfc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .96874 -1.364 .748 28.469 22.058)" gradientUnits="userSpaceOnUse"><stop class="bqx_aybef"/><stop offset="1" class="v9vtfdbbf"/></radialGradient><radialGradient id="iE1cFQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96757 -2.77802 0 11.773 11.352)" gradientUnits="userSpaceOnUse"><stop class="wds9vnbts"/><stop offset="1" class="e0a4yni_a"/></radialGradient><radialGradient id="i7LwsdU" cx="0" cy="0" r="1" gradientTransform="rotate(133.21 -.999 15.054)scale(1.76276 1.52752)" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="je7vqqg0r"/></radialGradient><radialGradient id="iDxhIib" cx="0" cy="0" r="1" gradientTransform="rotate(-74.924 22.46 8.476)scale(1.56984 3.21504)" gradientUnits="userSpaceOnUse"><stop class="fdomx0bpj"/><stop offset="1" class="li9m4eegn"/></radialGradient><filter id="ihxcN1c" width="16.5" height="19" x="14" y="8.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.258824 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/></filter><filter id="iIysgHd" width="18.5" height="7" x="13" y="20.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.513726 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10102" result="effect2_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.635294 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10102" result="effect3_innerShadow_18_10102"/></filter><filter id="ikaKI8b" width="14.5" height="15.75" x=".5" y="11.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.588235 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.631373 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10102" result="effect2_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.952941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10102" result="effect3_innerShadow_18_10102"/></filter><filter id="iyTnZQm" width="7.771" height="7.771" x="19.927" y="22.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.137255 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10102" result="effect2_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.180392 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10102" result="effect3_innerShadow_18_10102"/></filter><filter id="ifJ4PJd" width="3.116" height="3.151" x="22.106" y="25.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.137255 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10102"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10102" result="shape"/></filter><filter id="ip79uRb" width="6.25" height="6.5" x="19" y="11.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.768627 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10102" result="effect2_innerShadow_18_10102"/></filter><filter id="iszdnhc" width="10.225" height="5.5" x="2.775" y="13.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.513726 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/></filter><filter id="iwc0Qrq" width="3.225" height="3.747" x="4.384" y="23.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10102" stdDeviation=".2"/></filter><filter id="iioDCXb" width="7.771" height="7.771" x="4.948" y="22.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.137255 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10102" result="effect2_innerShadow_18_10102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.180392 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10102" result="effect3_innerShadow_18_10102"/></filter><filter id="iXeEhLe" width="3.116" height="3.151" x="7.084" y="25.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.137255 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10102"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10102" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ambulance" /></template>
<style>
.a0zxqubch {
  stop-color: var(--svg-color--df2b81, #DF2B81);
}

.a74tmo3pm {
  stop-color: var(--svg-color--43bcfc, #43BCFC);
}

.a8eqjq9ip {
  stop-color: var(--svg-color--d98e16, #D98E16);
}

.audz23byx {
  stop-color: var(--svg-color--77424d, #77424D);
  stop-opacity: 0;
}

.ay3u33bqk {
  d: path("M8.833 29.828a3.385 3.385 0 1 0 0-6.77a3.385 3.385 0 0 0 0 6.77");
}

.azm-e0-sg {
  d: path("M23.864 27.815c.64 0 1.158-.526 1.158-1.175c0-.65-.519-1.176-1.158-1.176c-.64 0-1.158.527-1.158 1.176s.518 1.175 1.158 1.175");
}

.bqx_aybef {
  stop-color: var(--svg-color--d8084b, #D8084B);
}

.c8g3lnome {
  fill-rule: evenodd;
  d: path("M29.795 9.174H14.417A2.5 2.5 0 0 1 16.5 8.057H28a2 2 0 0 1 1.795 1.117");
}

.cc2x5bbfu {
  d: path("M8.842 27.618c.64 0 1.158-.526 1.158-1.175c0-.65-.518-1.176-1.158-1.176s-1.158.527-1.158 1.176s.518 1.175 1.158 1.175");
}

.cq5_47bhh {
  stop-color: var(--svg-color--4decff, #4DECFF);
}

.cspwcz85c {
  d: path("M4.025 18.057H10.5a2.5 2.5 0 0 0 2.5-2.5v-1.5a1 1 0 0 0-1-1H8.002z");
}

.cxoyg5b7k {
  d: path("M28 23.557a1.5 1.5 0 0 1 1.5-1.5h.5v3h-.5a1.5 1.5 0 0 1-1.5-1.5");
}

.e0a4yni_a {
  stop-color: var(--svg-color--b3acbb, #B3ACBB);
}

.fankhfe2q {
  stop-color: var(--svg-color--f8a249, #F8A249);
}

.fazwaxb2r {
  stop-color: var(--svg-color--f4b9ff, #F4B9FF);
}

.fdomx0bpj {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
}

.fqh2grrds {
  fill: var(--svg-color--e8daf5, #E8DAF5);
  fill-rule: evenodd;
  d: path("M22 12.057a1 1 0 0 0-1 1v1h-1a1 1 0 1 0 0 2h1v1a1 1 0 1 0 2 0v-1h1a1 1 0 1 0 0-2h-1v-1a1 1 0 0 0-1-1");
}

.ft5dv1b6b {
  fill: none;
}

.fwdradjhp {
  stop-color: var(--svg-color--cfcecf, #CFCECF);
}

.fz6lhb-rg {
  stop-color: var(--svg-color--c10d63, #C10D63);
}

.gh88s7sup {
  stop-color: var(--svg-color--c2bcc9, #C2BCC9);
}

.hrbd7lbfs {
  stop-color: var(--svg-color--e3b1cf, #E3B1CF);
  stop-opacity: 0;
}

.htw3prbeg {
  stop-color: var(--svg-color--ee2947, #EE2947);
}

.ih1stibpr {
  stop-color: var(--svg-color--f4b9ff, #F4B9FF);
  stop-opacity: 0;
}

.ijonss59a {
  stop-color: var(--svg-color--ae6e8b, #AE6E8B);
}

.je7vqqg0r {
  stop-color: var(--svg-color--cabfd4, #CABFD4);
}

.jj7zhpb2o {
  stop-color: var(--svg-color--89888a, #89888A);
}

.k2waddo4y {
  d: path("M14 12.307a.25.25 0 0 0-.25-.25H9.762a2 2 0 0 0-1.566.755l-5.327 6.7A4 4 0 0 0 2 22v3.256a1.8 1.8 0 0 0 1.8 1.8h10a.2.2 0 0 0 .2-.2z");
}

.k766edczz {
  cx: 5.996px;
  cy: 25.132px;
  rx: 0.556px;
  ry: 1.825px;
}

.k7pff3lfr {
  stop-color: var(--svg-color--9685a5, #9685A5);
}

.kdjuolb5h {
  stop-color: var(--svg-color--98959a, #98959A);
}

.li9m4eegn {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
  stop-opacity: 0;
}

.m8iymzb7n {
  stop-color: var(--svg-color--ff4b9a, #FF4B9A);
}

.ml7lyl_zv {
  d: path("M14 10.557a2.5 2.5 0 0 1 2.5-2.5H28a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2H14.2a.2.2 0 0 1-.2-.2z");
}

.mxulxgbas {
  stop-color: var(--svg-color--4decff, #4DECFF);
  stop-opacity: 0;
}

.n2r4awbge {
  stop-color: var(--svg-color--f4def3, #F4DEF3);
}

.n2u2qnb8w {
  stop-color: var(--svg-color--e1c6f9, #E1C6F9);
}

.nfddcrbxt {
  stop-color: var(--svg-color--ff3a5b, #FF3A5B);
}

.ovjl_3bnl {
  stop-color: var(--svg-color--e6daec, #E6DAEC);
}

.p9vhezbkz {
  d: path("M10 11.657a.6.6 0 0 1 .6-.6h2.347a.6.6 0 0 1 .6.6v.4H10z");
}

.pm0enebiz {
  stop-color: var(--svg-color--f4f4f5, #F4F4F5);
  stop-opacity: 0;
}

.q2lci-pbk {
  stop-color: var(--svg-color--cfcecf, #CFCECF);
  stop-opacity: 0;
}

.qcgjw9paw {
  stop-color: var(--svg-color--b48bd2, #B48BD2);
  stop-opacity: 0;
}

.qkog218op {
  stop-color: var(--svg-color--9685a5, #9685A5);
  stop-opacity: 0;
}

.r7n0tbc-y {
  stop-color: var(--svg-color--e3152e, #E3152E);
}

.s_76kmb8c {
  stop-color: var(--svg-color--473276, #473276);
}

.salz2dthk {
  stop-color: var(--svg-color--d3d1d5, #D3D1D5);
}

.suif1cfgx {
  stop-color: var(--svg-color--c4bec2, #C4BEC2);
}

.tzq4t5bol {
  stop-color: var(--svg-color--b78cd6, #B78CD6);
}

.uggp-ibpr {
  stop-color: var(--svg-color--c4bec2, #C4BEC2);
  stop-opacity: 0;
}

.uhs84-bmt {
  stop-color: var(--svg-color--f4def3, #F4DEF3);
  stop-opacity: 0;
}

.uuxicacep {
  stop-color: var(--svg-color--f0d7ff, #F0D7FF);
}

.uy-elybtc {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
}

.v9vtfdbbf {
  stop-color: var(--svg-color--d8084b, #D8084B);
  stop-opacity: 0;
}

.vx3l9nuzv {
  stop-color: var(--svg-color--c2bcc9, #C2BCC9);
  stop-opacity: 0;
}

.vyc5y4bml {
  d: path("M23.813 30a3.385 3.385 0 1 0 0-6.77a3.385 3.385 0 0 0 0 6.77");
}

.wds9vnbts {
  stop-color: var(--svg-color--ded2e7, #DED2E7);
}

.wtjy1wbrs {
  stop-color: var(--svg-color--f4f4f5, #F4F4F5);
}

.x4dz_ej9d {
  d: path("M10.844 10.941a.93.93 0 1 1 1.86 0v.162h-1.86z");
}

.xk9_g7bcy {
  d: path("M2 25.057h1a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1h-.887a4 4 0 0 0-.113.944z");
}

.xkpht0bnp {
  d: path("M30 21.057H14v5.8c0 .11.09.2.2.2H28a2 2 0 0 0 2-2z");
}

.xs8ggnbvp {
  stop-color: var(--svg-color--98959a, #98959A);
  stop-opacity: 0;
}

.y-dcc-qsz {
  stop-color: var(--svg-color--89888a, #89888A);
  stop-opacity: 0;
}

.y1ui8gonf {
  stop-color: var(--svg-color--4d2775, #4D2775);
}

.y5jx_obwk {
  stop-color: var(--svg-color--f62747, #F62747);
}

.yzqbqq6pb {
  stop-color: var(--svg-color--e2c9f9, #E2C9F9);
}

.z37t2t5qb {
  stop-color: var(--svg-color--77424d, #77424D);
}

.zqg4l48wi {
  stop-color: var(--svg-color--f5d9ff, #F5D9FF);
}

.zwt_fzbmr {
  stop-color: var(--svg-color--59deff, #59DEFF);
}

</style>
