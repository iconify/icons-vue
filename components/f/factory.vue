<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iM8tF2b)" class="due5v1acy"/><path fill="url(#iXyXUQc)" class="due5v1acy"/><path fill="url(#iL1z0mb)" class="due5v1acy"/><path fill="url(#ikCcC1c)" class="xjfp9obrm"/><path fill="url(#i4Lve7c)" class="xjfp9obrm"/><path fill="url(#i7R4Qbd)" class="jzqugp24f"/><path fill="url(#iU4deJc)" class="j-4j8kb1y"/><path fill="url(#iEypRSc)" class="kksykhb_s"/><path fill="url(#i3MsWdG)" class="vbof4m43i"/><path fill="url(#i4rs43Y)" class="bkpwglb6d"/><path fill="url(#ii3oMcb)" class="gqmztnpfi"/><g class="j1m8-jbee"><path fill="url(#iQKt1Ub)" class="fqranqbtp"/><path fill="url(#ihdIkob)" class="fqranqbtp"/><path fill="url(#ivnRp1d)" class="fqranqbtp"/><path fill="url(#i56qf3m)" class="fqranqbtp"/><path fill="url(#isSMpHe)" class="fqranqbtp"/><path fill="url(#iiLJz3b)" class="fqranqbtp"/></g><g filter="url(#i12BYid)"><path fill="url(#i7qfgfb)" class="qlljiubie"/><path fill="url(#is2K0Wb)" class="qlljiubie"/><path fill="url(#isnUxyd)" class="qlljiubie"/></g><path fill="url(#iheQKNM)" class="qlljiubie"/><path fill="url(#is2K0Wb)" class="qlljiubie"/><g filter="url(#izI76Je)"><path fill="url(#i5WjGOe)" class="yf0xqgbds"/></g><g filter="url(#iXsCYde)"><path fill="url(#iUIdMNc)" class="e5yh0vbfc"/></g><g filter="url(#iKxqjeb)"><path fill="url(#ikJLtjd)" class="qjrrjab2d"/></g><g filter="url(#ihb3fLo)"><rect fill="url(#iwiGV8x)" class="m_u061blw"/></g><g filter="url(#iQZde2b)"><rect fill="url(#iUYkw3c)" class="gokrk2bbv"/></g><g filter="url(#iEtHm3b)"><rect fill="url(#irkP9Od)" class="ovg5f_iyz"/></g><g filter="url(#im1Ozzb)"><rect fill="url(#iuTJO8d)" class="gght2sbbo"/></g><g filter="url(#iIdFkDM)"><rect fill="url(#iNMb2Oe)" class="oeb_bxb9p"/></g><g filter="url(#is24k7b)"><rect fill="url(#iOO7ZFa)" class="snf7lwbfj"/></g><g filter="url(#i8clXid)"><rect fill="url(#iD4dtqb)" class="i6c_ibl_g"/></g><g filter="url(#il1vzml)"><rect fill="url(#iOxDvFc)" class="q28_0gbkx"/></g><g filter="url(#i5hHgmc)"><rect fill="url(#izfGYHT)" class="kz-4mnb_r"/></g><defs><linearGradient id="iM8tF2b" x1="6.75" x2="4.998" y1="13.004" y2="13.004" gradientUnits="userSpaceOnUse"><stop class="q2n50jbhi"/><stop offset="1" class="i3stmjbro"/></linearGradient><linearGradient id="iXyXUQc" x1="8" x2="7.594" y1="11.161" y2="11.161" gradientUnits="userSpaceOnUse"><stop class="gblco1b3b"/><stop offset="1" class="pnkgb9bmv"/></linearGradient><linearGradient id="iL1z0mb" x1="5.78" x2="5.344" y1="19.623" y2="18.771" gradientUnits="userSpaceOnUse"><stop class="c0yoqkuqx"/><stop offset="1" class="hntjfrb0f"/></linearGradient><linearGradient id="ikCcC1c" x1="12" x2="15" y1="10.936" y2="10.936" gradientUnits="userSpaceOnUse"><stop class="qndt4yurh"/><stop offset="1" class="txnvu0r2z"/></linearGradient><linearGradient id="i4Lve7c" x1="13.785" x2="13.785" y1="22.329" y2="14.948" gradientUnits="userSpaceOnUse"><stop class="zrwg55msv"/><stop offset="1" class="rhnri0b5x"/></linearGradient><linearGradient id="i7R4Qbd" x1="5" x2="7.133" y1="16.992" y2="16.992" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bgi8svgnr"/><stop offset="1" class="dougl1bib"/></linearGradient><linearGradient id="iU4deJc" x1="5" x2="7.133" y1="10.992" y2="10.992" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bgi8svgnr"/><stop offset="1" class="dougl1bib"/></linearGradient><linearGradient id="iEypRSc" x1="5" x2="7.133" y1="4.992" y2="4.992" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bgi8svgnr"/><stop offset="1" class="dougl1bib"/></linearGradient><linearGradient id="i3MsWdG" x1="12.005" x2="15.005" y1="27.495" y2="27.495" gradientUnits="userSpaceOnUse"><stop class="hiww04yvq"/><stop offset="1" class="nt02umbyo"/></linearGradient><linearGradient id="i4rs43Y" x1="12.005" x2="15.005" y1="21.495" y2="21.495" gradientUnits="userSpaceOnUse"><stop class="hiww04yvq"/><stop offset="1" class="nt02umbyo"/></linearGradient><linearGradient id="ii3oMcb" x1="12.005" x2="15.005" y1="15.495" y2="15.495" gradientUnits="userSpaceOnUse"><stop class="hiww04yvq"/><stop offset="1" class="nt02umbyo"/></linearGradient><linearGradient id="iQKt1Ub" x1="24" x2="29.592" y1="24.258" y2="29.233" gradientUnits="userSpaceOnUse"><stop class="n127xabwx"/><stop offset="1" class="ndcricc1o"/></linearGradient><linearGradient id="ihdIkob" x1="24" x2="24" y1="11.992" y2="12.754" gradientUnits="userSpaceOnUse"><stop class="x_y4-tsdi"/><stop class="khb-41b1u"/><stop offset="1" class="k9hyg_bys"/></linearGradient><linearGradient id="ivnRp1d" x1="18" x2="18.81" y1="23.626" y2="23.626" gradientUnits="userSpaceOnUse"><stop class="f75fxsb-a"/><stop offset="1" class="px3uxgbaw"/></linearGradient><linearGradient id="i56qf3m" x1="30" x2="29.013" y1="22.609" y2="22.609" gradientUnits="userSpaceOnUse"><stop class="xpd_c9bxo"/><stop offset="1" class="qzpkofb9z"/></linearGradient><linearGradient id="iiLJz3b" x1="30" x2="29.741" y1="20.124" y2="20.124" gradientUnits="userSpaceOnUse"><stop class="citc1m5dn"/><stop offset="1" class="sacfewspl"/></linearGradient><linearGradient id="i7qfgfb" x1="3.405" x2="18.518" y1="26.632" y2="26.632" gradientUnits="userSpaceOnUse"><stop class="zaxn906tp"/><stop offset="1" class="sswu58dzz"/></linearGradient><linearGradient id="is2K0Wb" x1="18.398" x2="17.066" y1="25.379" y2="25.379" gradientUnits="userSpaceOnUse"><stop class="qhi6ct63s"/><stop offset="1" class="yqo6fubne"/></linearGradient><linearGradient id="isnUxyd" x1="2" x2="2.896" y1="26.591" y2="26.591" gradientUnits="userSpaceOnUse"><stop class="b9z4h-fos"/><stop offset="1" class="d8p-gedva"/></linearGradient><linearGradient id="i5WjGOe" x1="4" x2="8.509" y1="28.886" y2="28.886" gradientUnits="userSpaceOnUse"><stop class="xx2zjebqs"/><stop offset="1" class="e2_0pfbli"/></linearGradient><linearGradient id="iUIdMNc" x1="11" x2="15.509" y1="28.886" y2="28.886" gradientUnits="userSpaceOnUse"><stop class="xx2zjebqs"/><stop offset="1" class="e2_0pfbli"/></linearGradient><linearGradient id="ikJLtjd" x1="21" x2="26.411" y1="28.517" y2="28.517" gradientUnits="userSpaceOnUse"><stop class="xx2zjebqs"/><stop offset="1" class="e2_0pfbli"/></linearGradient><linearGradient id="iwiGV8x" x1="20.124" x2="21.3" y1="16" y2="13.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iUYkw3c" x1="23.108" x2="24.285" y1="16" y2="13.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="irkP9Od" x1="26.093" x2="27.269" y1="16" y2="13.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iuTJO8d" x1="20.124" x2="21.3" y1="19" y2="16.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iNMb2Oe" x1="23.108" x2="24.285" y1="19" y2="16.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iOO7ZFa" x1="26.093" x2="27.269" y1="19" y2="16.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iD4dtqb" x1="20.124" x2="21.3" y1="22" y2="19.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="iOxDvFc" x1="23.108" x2="24.285" y1="22" y2="19.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><linearGradient id="izfGYHT" x1="26.093" x2="27.269" y1="22" y2="19.31" gradientUnits="userSpaceOnUse"><stop class="fcgwt_eqz"/><stop offset="1" class="cbg_xbcdf"/></linearGradient><filter id="i12BYid" width="16.25" height="13.25" x="1.75" y="16.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.505882 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.772549 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="izI76Je" width="5.4" height="3.15" x="3.75" y="26.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="iXsCYde" width="5.4" height="3.15" x="10.75" y="26.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="iKxqjeb" width="6.4" height="4.15" x="20.75" y="25.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.313726 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="ihb3fLo" width="2.442" height="2.242" x="19.77" y="14.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="iQZde2b" width="2.442" height="2.242" x="22.754" y="14.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="iEtHm3b" width="2.442" height="2.242" x="25.738" y="14.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="im1Ozzb" width="2.442" height="2.242" x="19.77" y="17.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="iIdFkDM" width="2.442" height="2.242" x="22.754" y="17.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="is24k7b" width="2.442" height="2.242" x="25.738" y="17.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="i8clXid" width="2.442" height="2.242" x="19.77" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="il1vzml" width="2.442" height="2.242" x="22.754" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><filter id="i5hHgmc" width="2.442" height="2.242" x="25.738" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6750"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.52549 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6750" result="effect2_innerShadow_18_6750"/></filter><radialGradient id="isSMpHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.66852 .6514 -1.08106 -1.10947 30 12.345)" gradientUnits="userSpaceOnUse"><stop class="xpd_c9bxo"/><stop offset="1" class="qzpkofb9z"/></radialGradient><radialGradient id="iheQKNM" cx="0" cy="0" r="1" gradientTransform="matrix(-.54244 -.18706 .24385 -.7071 10.262 20.49)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sl6fgzbgo"/><stop offset="1" class="i_wrqac0n"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:factory" /></template>
<style>
.b9z4h-fos {
  stop-color: var(--svg-color--726d76, #726D76);
}

.bgi8svgnr {
  stop-color: var(--svg-color--a43953, #A43953);
}

.bkpwglb6d {
  d: path("M15 7.992h-3v3h3z");
}

.c0yoqkuqx {
  stop-color: var(--svg-color--6c6a6e, #6C6A6E);
}

.cbg_xbcdf {
  stop-color: var(--svg-color--42a9ff, #42A9FF);
}

.citc1m5dn {
  stop-color: var(--svg-color--cac6cd, #CAC6CD);
}

.d8p-gedva {
  stop-color: var(--svg-color--726d76, #726D76);
  stop-opacity: 0;
}

.dougl1bib {
  stop-color: var(--svg-color--ff549c, #FF549C);
}

.due5v1acy {
  d: path("M5 20.872q0 .12.03.12h2.94q.03 0 .03-.12V4.992H5z");
}

.e2_0pfbli {
  stop-color: var(--svg-color--42394b, #42394B);
}

.e5yh0vbfc {
  d: path("M16 29.992h-5v-2.62c0-.21.17-.38.38-.38h4.24c.21 0 .38.17.38.38z");
}

.f75fxsb-a {
  stop-color: var(--svg-color--6d6573, #6D6573);
}

.fcgwt_eqz {
  stop-color: var(--svg-color--54e6ff, #54E6FF);
}

.fqranqbtp {
  d: path("M30 29.992H18v-16.87c0-.62.501-1.13 1.133-1.13h9.734c.622 0 1.133.5 1.133 1.13z");
}

.ft5dv1b6b {
  fill: none;
}

.gblco1b3b {
  stop-color: var(--svg-color--b1abb1, #B1ABB1);
}

.gght2sbbo {
  width: 1.992px;
  height: 1.992px;
  x: 20.02px;
  y: 17.008px;
  rx: 0.5px;
}

.gokrk2bbv {
  width: 1.992px;
  height: 1.992px;
  x: 23.004px;
  y: 14.008px;
  rx: 0.5px;
}

.gqmztnpfi {
  d: path("M15 2.502c0-.28-.23-.51-.51-.51h-1.98c-.28 0-.51.23-.51.51v2.49h3z");
}

.hiww04yvq {
  stop-color: var(--svg-color--a93751, #A93751);
}

.hntjfrb0f {
  stop-color: var(--svg-color--6c6a6e, #6C6A6E);
  stop-opacity: 0;
}

.i_wrqac0n {
  stop-color: var(--svg-color--cecbd0, #CECBD0);
  stop-opacity: 0;
}

.i3stmjbro {
  stop-color: var(--svg-color--79727d, #79727D);
}

.i6c_ibl_g {
  width: 1.992px;
  height: 1.992px;
  x: 20.02px;
  y: 20.008px;
  rx: 0.5px;
}

.j-4j8kb1y {
  d: path("M8 7.992H5v3h3z");
}

.j1m8-jbee {
  opacity: var(--svg-opacity--0-68, 0.68);
}

.jzqugp24f {
  d: path("M8 13.992H5v3h3z");
}

.k9hyg_bys {
  stop-color: var(--svg-color--b1b0b1, #B1B0B1);
  stop-opacity: 0;
}

.khb-41b1u {
  stop-color: var(--svg-color--b1b0b1, #B1B0B1);
  stop-opacity: 0.94;
}

.kksykhb_s {
  d: path("M8 2.502c0-.28-.23-.51-.51-.51H5.51c-.28 0-.51.23-.51.51v2.49h3z");
}

.kz-4mnb_r {
  width: 1.992px;
  height: 1.992px;
  x: 25.988px;
  y: 20.008px;
  rx: 0.5px;
}

.m_u061blw {
  width: 1.992px;
  height: 1.992px;
  x: 20.02px;
  y: 14.008px;
  rx: 0.5px;
}

.n127xabwx {
  stop-color: var(--svg-color--aaa2af, #AAA2AF);
}

.ndcricc1o {
  stop-color: var(--svg-color--bcb3c3, #BCB3C3);
}

.nt02umbyo {
  stop-color: var(--svg-color--ff5399, #FF5399);
}

.oeb_bxb9p {
  width: 1.992px;
  height: 1.992px;
  x: 23.004px;
  y: 17.008px;
  rx: 0.5px;
}

.ovg5f_iyz {
  width: 1.992px;
  height: 1.992px;
  x: 25.988px;
  y: 14.008px;
  rx: 0.5px;
}

.pnkgb9bmv {
  stop-color: var(--svg-color--b1abb1, #B1ABB1);
  stop-opacity: 0;
}

.px3uxgbaw {
  stop-color: var(--svg-color--6e6575, #6E6575);
  stop-opacity: 0;
}

.q28_0gbkx {
  width: 1.992px;
  height: 1.992px;
  x: 23.004px;
  y: 20.008px;
  rx: 0.5px;
}

.q2n50jbhi {
  stop-color: var(--svg-color--beb7c0, #BEB7C0);
}

.qhi6ct63s {
  stop-color: var(--svg-color--6f6574, #6F6574);
}

.qjrrjab2d {
  d: path("M27 29.992h-6v-3.637c0-.2.17-.363.381-.363h5.238c.21 0 .381.162.381.363z");
}

.qlljiubie {
  d: path("m2.21 20.902l7.245-3.63c.25-.12.54.06.54.33v2.79c0 .28.29.46.54.33L18 16.992v13H2v-8.77c0-.13.08-.26.21-.32");
}

.qndt4yurh {
  stop-color: var(--svg-color--84747f, #84747F);
}

.qzpkofb9z {
  stop-color: var(--svg-color--d9d5db, #D9D5DB);
  stop-opacity: 0;
}

.rhnri0b5x {
  stop-color: var(--svg-color--746e74, #746E74);
  stop-opacity: 0;
}

.sacfewspl {
  stop-color: var(--svg-color--cac6cd, #CAC6CD);
  stop-opacity: 0;
}

.sl6fgzbgo {
  stop-color: var(--svg-color--cecbd0, #CECBD0);
}

.snf7lwbfj {
  width: 1.992px;
  height: 1.992px;
  x: 25.988px;
  y: 17.008px;
  rx: 0.5px;
}

.sswu58dzz {
  stop-color: var(--svg-color--b3a8ba, #B3A8BA);
}

.txnvu0r2z {
  stop-color: var(--svg-color--dbd7df, #DBD7DF);
}

.vbof4m43i {
  d: path("M15 13.992h-3v3h3z");
}

.x_y4-tsdi {
  stop-color: var(--svg-color--b1b0b1, #B1B0B1);
}

.xjfp9obrm {
  d: path("M12 20.872q0 .12.03.12h2.94q.03 0 .03-.12V4.992h-3z");
}

.xpd_c9bxo {
  stop-color: var(--svg-color--d9d5db, #D9D5DB);
}

.xx2zjebqs {
  stop-color: var(--svg-color--544266, #544266);
}

.yf0xqgbds {
  d: path("M9 29.992H4v-2.62c0-.21.17-.38.38-.38h4.24c.21 0 .38.17.38.38z");
}

.yqo6fubne {
  stop-color: var(--svg-color--6f6574, #6F6574);
  stop-opacity: 0;
}

.zaxn906tp {
  stop-color: var(--svg-color--a19ba6, #A19BA6);
}

.zrwg55msv {
  stop-color: var(--svg-color--746e74, #746E74);
}

</style>
