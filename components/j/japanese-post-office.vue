<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixKwCHd)" class="tq28dvbxb"/><path fill="url(#isRKtAc)" class="tq28dvbxb"/><path fill="url(#iYEXGQd)" class="tq28dvbxb"/><path fill="url(#i3l8avb)" class="tq28dvbxb"/><g filter="url(#iSTaoGY)"><path fill="url(#i30WsHe)" class="knjra9b8p"/></g><path fill="url(#i0YLzCW)" class="sqdfzabtn"/><path fill="url(#ir3Fcud)" class="sqdfzabtn"/><path fill="url(#iuSAbyr)" class="sqdfzabtn"/><g filter="url(#iVrBHoZ)"><path fill="url(#iegwaGc)" class="ot0162b3r"/><path fill="url(#iSh5MPx)" class="ot0162b3r"/></g><g filter="url(#iHGRtDc)"><path fill="url(#ifnLDic)" class="mkwx9bbru"/></g><path fill="url(#ie1Gbme)" class="mkwx9bbru"/><path fill="url(#iWardue)" class="mkwx9bbru"/><g filter="url(#iXmejKU)"><path fill="url(#i6Hijxc)" class="qs4t70-oe"/></g><g filter="url(#ii5oQHP)"><path class="i5h8i5b3s"/></g><g filter="url(#iGvPjce)"><path fill="url(#ilkS7oc)" class="tfklsbzau"/><path fill="url(#iWyvZUc)" class="tfklsbzau"/><path fill="url(#iaczt4C)" class="tfklsbzau"/></g><g filter="url(#i7LdPXb)"><path class="mwebrvb4m"/></g><g filter="url(#iWCwvBe)"><path fill="url(#i1YYxnc)" class="kwr42wb0s"/><path fill="url(#ib5mg4c)" class="kwr42wb0s"/><path fill="url(#iQe6Ktb)" class="kwr42wb0s"/></g><path fill="url(#ivu2m8c)" class="m3ta9bbxu"/><path fill="url(#iJNN8vb)" class="m3ta9bbxu"/><path fill="url(#iHnfXLd)" class="m3ta9bbxu"/><g filter="url(#iF1q9Bc)"><path fill="url(#ippPBfl)" class="t_27mobaj"/><path fill="url(#iIPY3nd)" class="t_27mobaj"/></g><path fill="url(#ijajlCo)" class="l22xbcivy"/><path fill="url(#iqJPwJd)" class="l22xbcivy"/><g filter="url(#imhD5fe)"><path fill="url(#iHovWIe)" class="fciy3zbwv"/><path fill="url(#iRPmcMe)" class="fciy3zbwv"/></g><g filter="url(#iY1mBhd)"><path fill="url(#iV28TNb)" class="l28_ubjde"/><path fill="url(#iC2SvWT)" class="l28_ubjde"/><path fill="url(#i30t0Id)" class="l28_ubjde"/></g><g filter="url(#iY6RbSd)"><rect fill="url(#iJjmXPz)" class="ndhfbsvdh"/></g><g filter="url(#ils3RUq)"><rect fill="url(#i0jxlge)" class="tyqjkubac"/></g><g filter="url(#izC5Kfo)"><rect fill="url(#ieu5y0R)" class="lald86rys"/></g><g filter="url(#igVu5ib)"><rect fill="url(#ijZiHuc)" class="fnvkpg79g"/></g><defs><linearGradient id="ixKwCHd" x1="8.354" x2="2.995" y1="20.872" y2="20.872" gradientUnits="userSpaceOnUse"><stop offset=".069" class="rpoop2bll"/><stop offset=".283" class="vhzcczbnc"/></linearGradient><linearGradient id="isRKtAc" x1="2.995" x2="3.71" y1="27.469" y2="27.469" gradientUnits="userSpaceOnUse"><stop class="wrtyyh6jw"/><stop offset="1" class="vb6lqwbtd"/></linearGradient><linearGradient id="iYEXGQd" x1="4.241" x2="4.241" y1="11.75" y2="12.242" gradientUnits="userSpaceOnUse"><stop offset=".434" class="zkc8vx7zp"/><stop offset="1" class="umvc5bb9e"/></linearGradient><linearGradient id="i30WsHe" x1="3.773" x2="7.273" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="j4h895cqa"/><stop offset="1" class="i16vxr2vj"/></linearGradient><linearGradient id="i0YLzCW" x1="27.366" x2="21.46" y1="20.51" y2="20.51" gradientUnits="userSpaceOnUse"><stop class="j_ge80vxv"/><stop offset="1" class="okyxwjbay"/></linearGradient><linearGradient id="ir3Fcud" x1="23.639" x2="23.639" y1="11.881" y2="12.278" gradientUnits="userSpaceOnUse"><stop class="xxo9j9bcz"/><stop offset="1" class="yt8jkibkd"/></linearGradient><linearGradient id="iuSAbyr" x1="28.995" x2="28.361" y1="24.75" y2="24.75" gradientUnits="userSpaceOnUse"><stop class="cjulmij-n"/><stop offset="1" class="mk3umhn7m"/></linearGradient><linearGradient id="iegwaGc" x1="15.996" x2="15.996" y1="10.007" y2="12.01" gradientUnits="userSpaceOnUse"><stop class="y81cn3bck"/><stop offset="1" class="njfzecc_u"/></linearGradient><linearGradient id="ifnLDic" x1="15.995" x2="15.995" y1="1.5" y2="30.01" gradientUnits="userSpaceOnUse"><stop class="hsts_cbib"/><stop offset="1" class="l2exuobdf"/></linearGradient><linearGradient id="ie1Gbme" x1="14.534" x2="14.534" y1="30.803" y2="27.882" gradientUnits="userSpaceOnUse"><stop class="qd0vyqf9z"/><stop offset="1" class="ly034f_mg"/></linearGradient><linearGradient id="iWardue" x1="23.952" x2="23.089" y1="22.918" y2="22.918" gradientUnits="userSpaceOnUse"><stop class="r2s0i1bwe"/><stop offset="1" class="e76e_4bhx"/></linearGradient><linearGradient id="i6Hijxc" x1="25.227" x2="27.995" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ilkS7oc" x1="11.148" x2="16.585" y1="7.007" y2="7.007" gradientUnits="userSpaceOnUse"><stop class="oim4v9xmq"/><stop offset="1" class="km0lfg4me"/></linearGradient><linearGradient id="iWyvZUc" x1="20.179" x2="19.335" y1="7.25" y2="7.25" gradientUnits="userSpaceOnUse"><stop class="vqu65pb5k"/><stop offset="1" class="vd_t9mkkn"/></linearGradient><linearGradient id="iaczt4C" x1="16" x2="16" y1="5.937" y2="6.18" gradientUnits="userSpaceOnUse"><stop class="xpna0juws"/><stop offset="1" class="gyql-ibjv"/></linearGradient><linearGradient id="i1YYxnc" x1="11.149" x2="16.579" y1="11.015" y2="11.015" gradientUnits="userSpaceOnUse"><stop class="oim4v9xmq"/><stop offset="1" class="km0lfg4me"/></linearGradient><linearGradient id="ib5mg4c" x1="20.169" x2="19.326" y1="11.498" y2="11.498" gradientUnits="userSpaceOnUse"><stop class="vqu65pb5k"/><stop offset="1" class="vd_t9mkkn"/></linearGradient><linearGradient id="iQe6Ktb" x1="15.995" x2="15.995" y1="8.886" y2="9.368" gradientUnits="userSpaceOnUse"><stop class="xpna0juws"/><stop offset="1" class="gyql-ibjv"/></linearGradient><linearGradient id="ivu2m8c" x1="7.512" x2="8.997" y1="28.361" y2="28.361" gradientUnits="userSpaceOnUse"><stop class="fowrfmbpa"/><stop offset="1" class="wah7xr7ll"/></linearGradient><linearGradient id="iJNN8vb" x1="8.995" x2="8.694" y1="29.125" y2="29.125" gradientUnits="userSpaceOnUse"><stop class="hgoj_luur"/><stop offset="1" class="u1n3t6eas"/></linearGradient><linearGradient id="ippPBfl" x1="5.616" x2="9.554" y1="26.007" y2="26.007" gradientUnits="userSpaceOnUse"><stop class="ghzd3_bys"/><stop offset="1" class="i5-01cczj"/><stop offset="1" class="bky3jdbsb"/></linearGradient><linearGradient id="iIPY3nd" x1="10.005" x2="9.179" y1="26.719" y2="26.719" gradientUnits="userSpaceOnUse"><stop class="wv0sfi4-m"/><stop offset="1" class="mk_t22b0c"/></linearGradient><linearGradient id="iHovWIe" x1="12.996" x2="18.986" y1="26.975" y2="26.975" gradientUnits="userSpaceOnUse"><stop class="dn_h72bxs"/><stop offset="1" class="cwrj5u9cf"/></linearGradient><linearGradient id="iRPmcMe" x1="12.995" x2="14.323" y1="28.714" y2="28.714" gradientUnits="userSpaceOnUse"><stop class="mw58gzpvt"/><stop offset="1" class="xo2-n7btn"/></linearGradient><linearGradient id="iV28TNb" x1="15.996" x2="15.996" y1="1.997" y2="4" gradientUnits="userSpaceOnUse"><stop class="y81cn3bck"/><stop offset="1" class="njfzecc_u"/></linearGradient><linearGradient id="iC2SvWT" x1="15.995" x2="15.995" y1="1.884" y2="3" gradientUnits="userSpaceOnUse"><stop class="q_bu7ruzs"/><stop offset="1" class="z4pme-tqw"/></linearGradient><linearGradient id="iJjmXPz" x1="11.377" x2="15.048" y1="16.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="i0jxlge" x1="17.324" x2="20.995" y1="16.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ieu5y0R" x1="11.377" x2="15.048" y1="20.462" y2="20.462" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><linearGradient id="ijZiHuc" x1="17.324" x2="20.995" y1="20.462" y2="20.462" gradientUnits="userSpaceOnUse"><stop class="ttzh61lgu"/><stop offset="1" class="w3s_subrj"/></linearGradient><filter id="iSTaoGY" width="3.55" height="6.4" x="3.745" y="14.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.85098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><filter id="iVrBHoZ" width="28.25" height="2.25" x="1.995" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.184314 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="iHGRtDc" width="16.5" height="26.11" x="7.995" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.356863 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="iXmejKU" width="3.55" height="6.4" x="24.745" y="14.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><filter id="ii5oQHP" width="8.61" height="2.491" x="11.476" y="5.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6163" stdDeviation=".15"/></filter><filter id="iGvPjce" width="8.26" height="2.26" x="11.995" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.188235 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="i7LdPXb" width="8.6" height="4.506" x="11.486" y="8.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6163" stdDeviation=".15"/></filter><filter id="iWCwvBe" width="8.25" height="4.25" x="11.995" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.188235 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="iF1q9Bc" width="4.31" height="4.16" x="5.995" y="23.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.219608 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="imhD5fe" width="6.5" height="6.565" x="12.495" y="23.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0901961 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="iY1mBhd" width="18.25" height="2.25" x="6.995" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.184314 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/></filter><filter id="iY6RbSd" width="4.529" height="3.402" x="10.819" y="14.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><filter id="ils3RUq" width="4.529" height="3.402" x="16.766" y="14.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><filter id="izC5Kfo" width="4.529" height="3.402" x="10.819" y="18.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><filter id="igVu5ib" width="4.529" height="3.402" x="16.766" y="18.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.501961 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6163" result="effect2_innerShadow_18_6163"/></filter><radialGradient id="i3l8avb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.46509 0 0 -3.40625 7.46 27.094)" gradientUnits="userSpaceOnUse"><stop class="d2oa2pbee"/><stop offset="1" class="gfy_qrb8t"/></radialGradient><radialGradient id="iSh5MPx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68682 .67489 -1.26637 -3.16519 8.672 11.01)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="huoq88o_b"/><stop offset="1" class="kz4crsrxh"/></radialGradient><radialGradient id="iHnfXLd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0818 1.56249 -.8572 -1.1421 7.995 27.031)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="vy2ks1bcd"/><stop offset="1" class="ybvtm-byj"/></radialGradient><radialGradient id="ijajlCo" cx="0" cy="0" r="1" gradientTransform="matrix(1.56776 0 0 .6958 7.429 25.507)" gradientUnits="userSpaceOnUse"><stop class="hb6lo3b_c"/><stop offset="1" class="jjhxjrbth"/></radialGradient><radialGradient id="iqJPwJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.73071 0 0 1.34935 6.995 25.51)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="sm6qw3brr"/><stop offset="1" class="j01na4b8k"/></radialGradient><radialGradient id="i30t0Id" cx="0" cy="0" r="1" gradientTransform="rotate(144.093 12.147 5.132)scale(1.4236 1.54212)" gradientUnits="userSpaceOnUse"><stop class="eawq8ibpn"/><stop offset="1" class="rp9v9hbtr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:japanese-post-office" /></template>
<style>
.bky3jdbsb {
  stop-color: var(--svg-color--ff874b, #FF874B);
}

.cjulmij-n {
  stop-color: var(--svg-color--dfdbe1, #DFDBE1);
}

.cwrj5u9cf {
  stop-color: var(--svg-color--473d4f, #473D4F);
}

.d2oa2pbee {
  stop-color: var(--svg-color--6b5972, #6B5972);
}

.dn_h72bxs {
  stop-color: var(--svg-color--524163, #524163);
}

.e76e_4bhx {
  stop-color: var(--svg-color--d9d4db, #D9D4DB);
  stop-opacity: 0;
}

.eawq8ibpn {
  stop-color: var(--svg-color--ffad6b, #FFAD6B);
}

.fciy3zbwv {
  d: path("M18.985 30.01h-5.99v-4.68c0-.768.609-1.385 1.368-1.385h3.254a1.39 1.39 0 0 1 1.378 1.395v4.67z");
}

.fnvkpg79g {
  width: 3.979px;
  height: 3.002px;
  x: 17.016px;
  y: 18.961px;
  rx: 0.5px;
}

.fowrfmbpa {
  stop-color: var(--svg-color--574167, #574167);
}

.ft5dv1b6b {
  fill: none;
}

.gfy_qrb8t {
  stop-color: var(--svg-color--6b5972, #6B5972);
  stop-opacity: 0;
}

.ghzd3_bys {
  stop-color: var(--svg-color--ee3124, #EE3124);
}

.gyql-ibjv {
  stop-color: var(--svg-color--ff623e, #FF623E);
  stop-opacity: 0;
}

.hb6lo3b_c {
  stop-color: var(--svg-color--6a567a, #6A567A);
}

.hgoj_luur {
  stop-color: var(--svg-color--524958, #524958);
}

.hsts_cbib {
  stop-color: var(--svg-color--af9faa, #AF9FAA);
}

.huoq88o_b {
  stop-color: var(--svg-color--a33f2c, #A33F2C);
}

.i16vxr2vj {
  stop-color: var(--svg-color--3c99e4, #3C99E4);
}

.i5-01cczj {
  stop-color: var(--svg-color--ff8213, #FF8213);
}

.i5h8i5b3s {
  fill: var(--svg-color--775461, #775461);
  d: path("M19.316 8.14h-7.08c-.25 0-.46-.188-.46-.432V6.683c0-.235.2-.433.46-.433h7.09c.25 0 .46.188.46.433v1.016a.463.463 0 0 1-.47.442");
}

.j_ge80vxv {
  stop-color: var(--svg-color--bfb6c6, #BFB6C6);
}

.j01na4b8k {
  stop-color: var(--svg-color--1d1624, #1D1624);
}

.j4h895cqa {
  stop-color: var(--svg-color--50c5ff, #50C5FF);
}

.jjhxjrbth {
  stop-color: var(--svg-color--3e2a4e, #3E2A4E);
}

.km0lfg4me {
  stop-color: var(--svg-color--ff8949, #FF8949);
}

.knjra9b8p {
  d: path("M6.385 21.01h-1.78c-.34 0-.61-.27-.61-.61v-4.78c0-.34.27-.61.61-.61h1.78c.34 0 .61.27.61.61v4.78c0 .34-.27.61-.61.61");
}

.kwr42wb0s {
  d: path("M19.995 9.47c0-.25-.2-.46-.46-.46h-7.08c-.25 0-.46.2-.46.46v1.08c0 .25.2.46.46.46h2.08c.25 0 .46.2.46.46v1.08c0 .25.2.46.46.46h1.08c.25 0 .46-.2.46-.46v-1.09c0-.25.2-.46.46-.46h2.08c.25 0 .46-.2.46-.46z");
}

.kz4crsrxh {
  stop-color: var(--svg-color--a33f2c, #A33F2C);
  stop-opacity: 0;
}

.l22xbcivy {
  d: path("M8.495 26.01h-1c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1c.28 0 .5.22.5.5c0 .27-.22.5-.5.5");
}

.l28_ubjde {
  d: path("M6.995 3c0-.55.45-1 1-1h16c.55 0 1 .45 1 1s-.45 1-1 1h-16c-.55 0-1-.44-1-1");
}

.l2exuobdf {
  stop-color: var(--svg-color--bcb1c2, #BCB1C2);
}

.lald86rys {
  width: 3.979px;
  height: 3.002px;
  x: 11.069px;
  y: 18.961px;
  rx: 0.5px;
}

.ly034f_mg {
  stop-color: var(--svg-color--b8adc0, #B8ADC0);
  stop-opacity: 0;
}

.m3ta9bbxu {
  d: path("M8.995 26.72h-2v3.29h2z");
}

.mk_t22b0c {
  stop-color: var(--svg-color--ffb462, #FFB462);
  stop-opacity: 0;
}

.mk3umhn7m {
  stop-color: var(--svg-color--dfdbe1, #DFDBE1);
  stop-opacity: 0;
}

.mkwx9bbru {
  d: path("M7.995 4v26.01h16V4z");
}

.mw58gzpvt {
  stop-color: var(--svg-color--66507e, #66507E);
}

.mwebrvb4m {
  fill: var(--svg-color--775461, #775461);
  d: path("M19.786 9.668c0-.244-.2-.45-.46-.45h-7.08c-.25 0-.46.196-.46.45v1.055c0 .244.2.449.46.449h2.08c.25 0 .46.195.46.45v1.054c0 .244.2.449.46.449h1.08c.25 0 .46-.195.46-.45v-1.064c0-.244.2-.449.46-.449h2.08c.25 0 .46-.195.46-.45z");
}

.ndhfbsvdh {
  width: 3.979px;
  height: 3.002px;
  x: 11.069px;
  y: 14.997px;
  rx: 0.5px;
}

.njfzecc_u {
  stop-color: var(--svg-color--e23f3c, #E23F3C);
}

.oim4v9xmq {
  stop-color: var(--svg-color--ff534f, #FF534F);
}

.okyxwjbay {
  stop-color: var(--svg-color--a297a0, #A297A0);
}

.ot0162b3r {
  d: path("M1.995 11.01c0-.55.45-1 1-1h26c.55 0 1 .45 1 1s-.45 1-1 1h-26c-.55 0-1-.45-1-1");
}

.q_bu7ruzs {
  stop-color: var(--svg-color--ff9853, #FF9853);
}

.qd0vyqf9z {
  stop-color: var(--svg-color--b8adc0, #B8ADC0);
}

.qs4t70-oe {
  d: path("M27.385 21.01h-1.78c-.34 0-.61-.27-.61-.61v-4.78c0-.34.27-.61.61-.61h1.78c.34 0 .61.27.61.61v4.78c0 .34-.27.61-.61.61");
}

.r2s0i1bwe {
  stop-color: var(--svg-color--d9d4db, #D9D4DB);
}

.rp9v9hbtr {
  stop-color: var(--svg-color--ffad6b, #FFAD6B);
  stop-opacity: 0;
}

.rpoop2bll {
  stop-color: var(--svg-color--645768, #645768);
}

.sm6qw3brr {
  stop-color: var(--svg-color--1d1624, #1D1624);
  stop-opacity: 0;
}

.sqdfzabtn {
  d: path("M28.995 11.01h-18v19h18z");
}

.t_27mobaj {
  d: path("M9.105 28.01h-2.21c-.49 0-.9-.4-.9-.9V24.9c0-.49.4-.9.9-.9h2.21c.49 0 .9.4.9.9v2.21c-.01.5-.41.9-.9.9");
}

.tfklsbzau {
  d: path("M19.535 8.01h-7.08c-.25 0-.46-.2-.46-.46V6.46c0-.25.2-.46.46-.46h7.09c.25 0 .46.2.46.46v1.08c-.01.26-.21.47-.47.47");
}

.tq28dvbxb {
  d: path("M20.995 11.01h-18v19h18z");
}

.ttzh61lgu {
  stop-color: var(--svg-color--58e6ff, #58E6FF);
}

.tyqjkubac {
  width: 3.979px;
  height: 3.002px;
  x: 17.016px;
  y: 14.997px;
  rx: 0.5px;
}

.u1n3t6eas {
  stop-color: var(--svg-color--524958, #524958);
  stop-opacity: 0;
}

.umvc5bb9e {
  stop-color: var(--svg-color--714960, #714960);
  stop-opacity: 0;
}

.vb6lqwbtd {
  stop-color: var(--svg-color--79757d, #79757D);
  stop-opacity: 0;
}

.vd_t9mkkn {
  stop-color: var(--svg-color--ffaa58, #FFAA58);
  stop-opacity: 0;
}

.vhzcczbnc {
  stop-color: var(--svg-color--978d9b, #978D9B);
}

.vqu65pb5k {
  stop-color: var(--svg-color--ffaa58, #FFAA58);
}

.vy2ks1bcd {
  stop-color: var(--svg-color--402749, #402749);
}

.w3s_subrj {
  stop-color: var(--svg-color--44b8ff, #44B8FF);
}

.wah7xr7ll {
  stop-color: var(--svg-color--695e72, #695E72);
}

.wrtyyh6jw {
  stop-color: var(--svg-color--79757d, #79757D);
}

.wv0sfi4-m {
  stop-color: var(--svg-color--ffb462, #FFB462);
}

.xo2-n7btn {
  stop-color: var(--svg-color--66507e, #66507E);
  stop-opacity: 0;
}

.xpna0juws {
  stop-color: var(--svg-color--ff623e, #FF623E);
}

.xxo9j9bcz {
  stop-color: var(--svg-color--875c74, #875C74);
}

.y81cn3bck {
  stop-color: var(--svg-color--ff8946, #FF8946);
}

.ybvtm-byj {
  stop-color: var(--svg-color--402749, #402749);
  stop-opacity: 0;
}

.yt8jkibkd {
  stop-color: var(--svg-color--875c74, #875C74);
  stop-opacity: 0;
}

.z4pme-tqw {
  stop-color: var(--svg-color--ff9853, #FF9853);
  stop-opacity: 0;
}

.zkc8vx7zp {
  stop-color: var(--svg-color--714960, #714960);
}

</style>
