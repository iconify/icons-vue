<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEhSwLZ)" class="w5xxv7bof"/><path fill="url(#izaPVmd)" class="w5xxv7bof"/><path fill="url(#iKEEhjd)" class="w5xxv7bof"/><path fill="url(#i1EzO1d)" class="w5xxv7bof"/><path fill="url(#i34sImb)" class="w5xxv7bof"/><path fill="url(#iQXovEb)" class="w5xxv7bof"/><g filter="url(#iWUAnGb)"><path fill="url(#ijELUrd)" clip-rule="evenodd" class="be5nxubao"/></g><path fill="url(#iercCzd)" class="jmcmn2tah"/><path fill="url(#iYgxwke)" class="jmcmn2tah"/><path fill="url(#iRD6nqc)" class="jmcmn2tah"/><path fill="url(#iIiGXUd)" class="jmcmn2tah"/><path fill="url(#inFSbte)" class="jmcmn2tah"/><g filter="url(#iqKyxeb)"><path fill="url(#iQVIf2c)" class="yh009tbwt"/></g><g filter="url(#iSNgSCc)"><path stroke="url(#i2WLbBe)" class="s18hfjbgv"/></g><g filter="url(#iuyppLd)"><path class="hknia-rwu"/></g><g filter="url(#iXyopoc)"><path class="sgh_ghb0n"/></g><g filter="url(#iQtfFbe)"><path class="ef0d13b4f"/></g><g filter="url(#iNCIpEd)"><path fill="url(#imNL7Id)" class="hw3x87bxg"/><path fill="url(#iF6L7Nd)" class="hw3x87bxg"/></g><g filter="url(#iZ1eXpn)"><path class="x-0itb8qp"/></g><g filter="url(#iMLtcmc)"><path fill="url(#ixFvdEb)" class="d4arsyi7b"/><path fill="url(#izwAxod)" class="d4arsyi7b"/><path fill="url(#i0H6FMb)" class="d4arsyi7b"/></g><g filter="url(#i78PLTc)"><path fill="url(#iAcI9re)" class="n20kmrqgp"/><path fill="url(#iQ4eLQd)" class="n20kmrqgp"/><path fill="url(#izJYbBd)" class="n20kmrqgp"/></g><g filter="url(#imFKOBc)"><rect fill="url(#iJwxmGc)" class="d9rzg837z"/><rect fill="url(#i3tyUGe)" class="d9rzg837z"/><rect fill="url(#ip06NEl)" class="d9rzg837z"/></g><g filter="url(#iceJjyy)"><path fill="url(#iC4OOQL)" class="v1iieqbzg"/><path fill="url(#i8A8QQc)" class="v1iieqbzg"/><path fill="url(#iQJjGCc)" class="v1iieqbzg"/></g><g filter="url(#id3rjOd)"><path fill="url(#iDXzj5c)" clip-rule="evenodd" class="g9bzf2-1w"/></g><g filter="url(#i9SzP9p)"><path fill="url(#i5QMVFb)" class="k2se42b6d"/><path fill="url(#in6pDAd)" class="k2se42b6d"/></g><g filter="url(#iTXgMLe)"><path fill="url(#iz1UFwX)" class="le_q_-b3j"/></g><g filter="url(#idl0cYb)"><path fill="url(#irbYmnb)" clip-rule="evenodd" class="ev4t1k4ei"/></g><g filter="url(#iTmOKqe)"><path fill="url(#iesgETd)" clip-rule="evenodd" class="iq-1bsb7s"/></g><g filter="url(#ih4gf4c)"><path fill="url(#iyincqe)" class="s2t2-vb8g"/></g><path fill="url(#inPkHne)" class="zrz2f6bga"/><path fill="url(#iZTwXOk)" class="zrz2f6bga"/><path fill="url(#i6BBYpc)" class="zrz2f6bga"/><g filter="url(#iFStGSc)"><path stroke="url(#ia7OI3X)" class="zc8cbbcqr"/></g><g filter="url(#isDIgfc)"><path stroke="url(#i8PQwBe)" class="tg5ylwgwl"/></g><defs><linearGradient id="iEhSwLZ" x1="4.859" x2="8.89" y1="9.56" y2="9.56" gradientUnits="userSpaceOnUse"><stop class="fttdieqjx"/><stop offset="1" class="q6y64jbmq"/></linearGradient><linearGradient id="izaPVmd" x1="4.782" x2="5.641" y1="10.332" y2="10.332" gradientUnits="userSpaceOnUse"><stop class="ddyosdb5j"/><stop offset="1" class="g84v3qwrm"/></linearGradient><linearGradient id="i1EzO1d" x1="7.298" x2="6.516" y1="11.457" y2="10.207" gradientUnits="userSpaceOnUse"><stop class="c77ewib5w"/><stop offset="1" class="e0i1j3bua"/></linearGradient><linearGradient id="iQXovEb" x1="9.301" x2="8.342" y1="8.473" y2="8.473" gradientUnits="userSpaceOnUse"><stop class="prq6w6vez"/><stop offset="1" class="u0h_oitmh"/></linearGradient><linearGradient id="ijELUrd" x1="5.923" x2="4.751" y1="8.793" y2="8.793" gradientUnits="userSpaceOnUse"><stop class="fuc8exbfi"/><stop offset="1" class="g6p7ukb-m"/></linearGradient><linearGradient id="iercCzd" x1="4.892" x2="27.361" y1="21.353" y2="21.353" gradientUnits="userSpaceOnUse"><stop class="kw4rn-bvy"/><stop offset="1" class="mt-6s8beo"/><stop offset="1" class="y4zdbibkp"/></linearGradient><linearGradient id="iYgxwke" x1="27.563" x2="26.375" y1="24.723" y2="24.723" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="iIiGXUd" x1="4.753" x2="6.16" y1="27.08" y2="27.08" gradientUnits="userSpaceOnUse"><stop class="n8s4uabpq"/><stop offset="1" class="g24k1cu4h"/></linearGradient><linearGradient id="inFSbte" x1="20.297" x2="19.672" y1="9.222" y2="9.988" gradientUnits="userSpaceOnUse"><stop offset=".293" class="uuaff7f3s"/><stop offset="1" class="s140eac2l"/></linearGradient><linearGradient id="iQVIf2c" x1="7.955" x2="15.829" y1="23.809" y2="23.809" gradientUnits="userSpaceOnUse"><stop class="rrzt1d-pe"/><stop offset=".492" class="sjhtg-xeu"/><stop offset="1" class="vuad6pb7r"/><stop offset="1" class="g--emvsmv"/></linearGradient><linearGradient id="i2WLbBe" x1="9.282" x2="9.282" y1="21.623" y2="29.467" gradientUnits="userSpaceOnUse"><stop class="vuopvs98u"/><stop offset="1" class="k--2kgbfo"/></linearGradient><linearGradient id="imNL7Id" x1="19.245" x2="26.704" y1="20.658" y2="20.658" gradientUnits="userSpaceOnUse"><stop class="leu9f3p8r"/><stop offset="1" class="vuad6pb7r"/><stop offset="1" class="ph8qe-b3q"/></linearGradient><linearGradient id="iF6L7Nd" x1="19.245" x2="20.305" y1="22.148" y2="22.148" gradientUnits="userSpaceOnUse"><stop class="ps3vji8sb"/><stop offset="1" class="y2v_dxbqp"/></linearGradient><linearGradient id="ixFvdEb" x1="7.717" x2="12.86" y1="20.845" y2="20.851" gradientUnits="userSpaceOnUse"><stop class="ns11g_bru"/><stop offset="1" class="o4ld_ebqr"/></linearGradient><linearGradient id="izwAxod" x1="11.614" x2="11.561" y1="20.997" y2="20.707" gradientUnits="userSpaceOnUse"><stop class="qxybjpb0z"/><stop offset="1" class="cr5kk2b8j"/></linearGradient><linearGradient id="i0H6FMb" x1="15.812" x2="15.449" y1="19.073" y2="19.134" gradientUnits="userSpaceOnUse"><stop class="dj9gj5h9u"/><stop offset="1" class="b8_bbwyzq"/><stop offset="1" class="z_h7t_gnx"/></linearGradient><linearGradient id="iAcI9re" x1="8.11" x2="13.174" y1="23.992" y2="24.002" gradientUnits="userSpaceOnUse"><stop class="c41s7dbeu"/><stop offset="1" class="josyhbbcc"/></linearGradient><linearGradient id="iQ4eLQd" x1="11.931" x2="11.931" y1="24.566" y2="24.245" gradientUnits="userSpaceOnUse"><stop class="qxybjpb0z"/><stop offset="1" class="cr5kk2b8j"/></linearGradient><linearGradient id="izJYbBd" x1="16.345" x2="15.813" y1="23.019" y2="23.019" gradientUnits="userSpaceOnUse"><stop class="dj9gj5h9u"/><stop offset="1" class="b8_bbwyzq"/><stop offset="1" class="z_h7t_gnx"/></linearGradient><linearGradient id="iJwxmGc" x1="8.161" x2="13.14" y1="26.803" y2="26.822" gradientUnits="userSpaceOnUse"><stop class="c41s7dbeu"/><stop offset="1" class="josyhbbcc"/></linearGradient><linearGradient id="i3tyUGe" x1="11.917" x2="11.917" y1="27.076" y2="26.924" gradientUnits="userSpaceOnUse"><stop class="qxybjpb0z"/><stop offset="1" class="cr5kk2b8j"/></linearGradient><linearGradient id="ip06NEl" x1="16.257" x2="15.735" y1="26.338" y2="26.338" gradientUnits="userSpaceOnUse"><stop class="dj9gj5h9u"/><stop offset="1" class="b8_bbwyzq"/><stop offset="1" class="z_h7t_gnx"/></linearGradient><linearGradient id="iC4OOQL" x1="18.391" x2="25.266" y1="22.144" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="jlcs8ub8p"/><stop offset="1" class="npvtk6bwu"/></linearGradient><linearGradient id="i8A8QQc" x1="22.29" x2="22.227" y1="22.121" y2="21.839" gradientUnits="userSpaceOnUse"><stop class="olvjm8b_s"/><stop offset="1" class="kv15-1vjl"/></linearGradient><linearGradient id="iQJjGCc" x1="26.399" x2="26.04" y1="20.058" y2="20.136" gradientUnits="userSpaceOnUse"><stop class="i234zr5bb"/><stop offset="1" class="b8_bbwyzq"/></linearGradient><linearGradient id="iDXzj5c" x1="27.843" x2="25.064" y1="26.285" y2="26.285" gradientUnits="userSpaceOnUse"><stop class="yc9ijacob"/><stop offset=".353" class="yc9ijacob"/><stop offset=".521" class="tn5jawbxu"/><stop offset="1" class="tn5jawbxu"/><stop offset="1" class="g_98g8-dm"/></linearGradient><linearGradient id="i5QMVFb" x1="23.334" x2="17.821" y1="11.922" y2="11.922" gradientUnits="userSpaceOnUse"><stop class="skv-xe6bz"/><stop offset="1" class="k5us68bov"/></linearGradient><linearGradient id="in6pDAd" x1="22.629" x2="22.219" y1="11.645" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="tbf7krb3d"/><stop offset="1" class="ak0q5fits"/></linearGradient><linearGradient id="iz1UFwX" x1="14.816" x2="11.454" y1="9.934" y2="9.934" gradientUnits="userSpaceOnUse"><stop class="rvxvvfb_b"/><stop offset="1" class="tn5jawbxu"/></linearGradient><linearGradient id="irbYmnb" x1="6.562" x2="4.892" y1="17.075" y2="17.075" gradientUnits="userSpaceOnUse"><stop class="sgjwsvb6p"/><stop offset="1" class="n5-mfdbhl"/></linearGradient><linearGradient id="iesgETd" x1="6.32" x2="4.892" y1="25.311" y2="25.311" gradientUnits="userSpaceOnUse"><stop class="tn5jawbxu"/><stop offset="1" class="skdjsiuew"/></linearGradient><linearGradient id="iyincqe" x1="9.477" x2="9.29" y1="11.378" y2="11.972" gradientUnits="userSpaceOnUse"><stop offset=".328" class="mje4td9lu"/><stop offset="1" class="baos_pj2d"/></linearGradient><linearGradient id="inPkHne" x1="16" x2="16" y1="4.219" y2="16.614" gradientUnits="userSpaceOnUse"><stop class="pnrdq1_ru"/><stop offset="1" class="j-db6kb8p"/></linearGradient><linearGradient id="iZTwXOk" x1="10.632" x2="10.976" y1="8.182" y2="8.599" gradientUnits="userSpaceOnUse"><stop class="ec1gcdb8n"/><stop offset="1" class="fp8oh5goq"/></linearGradient><linearGradient id="ia7OI3X" x1="28.012" x2="16.197" y1="15.401" y2="6.135" gradientUnits="userSpaceOnUse"><stop class="b8ugf-bfs"/><stop offset="1" class="p81nog0zt"/></linearGradient><linearGradient id="i8PQwBe" x1="7.86" x2="4.503" y1="10.55" y2="7.894" gradientUnits="userSpaceOnUse"><stop class="mq5sflbrn"/><stop offset="1" class="vfrcjhz5y"/></linearGradient><filter id="iWUAnGb" width="1.507" height="1.052" x="4.892" y="8.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.403922 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iqKyxeb" width="7.252" height="12.43" x="7.955" y="17.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.0352941 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iSNgSCc" width=".9" height="8.912" x="8.332" y="20.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".15"/></filter><filter id="iuyppLd" width="7.781" height="1.501" x="7.641" y="23.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><filter id="iXyopoc" width="7.651" height="2.876" x="7.648" y="19.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><filter id="iQtfFbe" width="7.781" height="1.501" x="7.641" y="26.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><filter id="iNCIpEd" width="5.402" height="6.393" x="18.995" y="17.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0235294 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iZ1eXpn" width="5.781" height="2.484" x="18.938" y="20.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><filter id="iMLtcmc" width="9.486" height="3.56" x="6.481" y="18.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.211765 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="i78PLTc" width="9.408" height="2.178" x="6.876" y="22.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.211765 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="imFKOBc" width="9.252" height="1.068" x="6.948" y="26.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.211765 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iceJjyy" width="9.464" height="3.832" x="17.122" y="19.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.243137 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="id3rjOd" width="2.955" height="1.102" x="24.406" y="25.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.403922 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="i9SzP9p" width="6.194" height="1.008" x="17.821" y="11.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.403922 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iTXgMLe" width="3.576" height=".959" x="10.658" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.403922 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="idl0cYb" width="3.039" height="1.175" x="4.892" y="16.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.403922 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="iTmOKqe" width="1.511" height="1.101" x="4.892" y="24.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.45098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5934"/></filter><filter id="ih4gf4c" width="2.78" height="1.996" x="7.466" y="10.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".15"/></filter><filter id="iFStGSc" width="13.463" height="11.011" x="16.427" y="5.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><filter id="isDIgfc" width="3.216" height="5.067" x="5.798" y="5.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5934" stdDeviation=".25"/></filter><radialGradient id="iKEEhjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 1.53259 0 7.61 11.988)" gradientUnits="userSpaceOnUse"><stop class="c77ewib5w"/><stop offset="1" class="e0i1j3bua"/></radialGradient><radialGradient id="i34sImb" cx="0" cy="0" r="1" gradientTransform="rotate(103.367 1.436 5.394)scale(1.48692 1.55915)" gradientUnits="userSpaceOnUse"><stop class="xd9iq1g7o"/><stop offset="1" class="i9m24xbnn"/></radialGradient><radialGradient id="iRD6nqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.09375 -1.03285 0 27.627 15.082)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="h-6n87bth"/><stop offset="1" class="wyry6cbrh"/></radialGradient><radialGradient id="i6BBYpc" cx="0" cy="0" r="1" gradientTransform="matrix(3.60346 2.92146 -1.70945 2.1085 16.932 4.219)" gradientUnits="userSpaceOnUse"><stop class="tim3_4bcp"/><stop offset="1" class="fh842tbny"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:derelict-house" /></template>
<style>
.ak0q5fits {
  stop-color: var(--svg-color--a64f31, #A64F31);
  stop-opacity: 0;
}

.b8_bbwyzq {
  stop-color: var(--svg-color--ae796a, #AE796A);
  stop-opacity: 0;
}

.b8ugf-bfs {
  stop-color: var(--svg-color--f35b47, #F35B47);
}

.baos_pj2d {
  stop-color: var(--svg-color--ab4d46, #AB4D46);
  stop-opacity: 0;
}

.be5nxubao {
  fill-rule: evenodd;
  d: path("M4.892 9.293V8.292l1.195.174a.364.364 0 0 1-.02.723z");
}

.c41s7dbeu {
  stop-color: var(--svg-color--76504f, #76504F);
}

.c77ewib5w {
  stop-color: var(--svg-color--ae6d45, #AE6D45);
}

.cr5kk2b8j {
  stop-color: var(--svg-color--6c3a44, #6C3A44);
  stop-opacity: 0;
}

.d4arsyi7b {
  d: path("m15.102 18.182l-8.225 1.443a.465.465 0 0 0-.394.492c.042.475.147.899.238 1.212a.5.5 0 0 0 .567.347l8.171-1.425a.487.487 0 0 0 .404-.543a21 21 0 0 0-.189-1.136a.494.494 0 0 0-.572-.39");
}

.d9rzg837z {
  width: 9.152px;
  height: 1.018px;
  x: 6.948px;
  y: 26.037px;
  rx: 0.5px;
}

.ddyosdb5j {
  stop-color: var(--svg-color--8e6543, #8E6543);
}

.dj9gj5h9u {
  stop-color: var(--svg-color--97695f, #97695F);
}

.e0i1j3bua {
  stop-color: var(--svg-color--ae6d45, #AE6D45);
  stop-opacity: 0;
}

.ec1gcdb8n {
  stop-color: var(--svg-color--ba533c, #BA533C);
}

.ef0d13b4f {
  fill: var(--svg-color--1d0f34, #1D0F34);
  d: path("M8.141 26.805h6.781v.501H8.141z");
}

.ev4t1k4ei {
  fill-rule: evenodd;
  d: path("M4.892 17.637v-1.124l2.726.193a.336.336 0 0 1 .008.67z");
}

.fh842tbny {
  stop-color: var(--svg-color--ff8739, #FF8739);
  stop-opacity: 0;
}

.fp8oh5goq {
  stop-color: var(--svg-color--ba533c, #BA533C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fttdieqjx {
  stop-color: var(--svg-color--d89763, #D89763);
}

.fuc8exbfi {
  stop-color: var(--svg-color--c87d41, #C87D41);
}

.g_98g8-dm {
  stop-color: var(--svg-color--d08049, #D08049);
}

.g--emvsmv {
  stop-color: var(--svg-color--31254b, #31254B);
}

.g24k1cu4h {
  stop-color: var(--svg-color--926b50, #926B50);
  stop-opacity: 0;
}

.g6p7ukb-m {
  stop-color: var(--svg-color--8d5b33, #8D5B33);
}

.g84v3qwrm {
  stop-color: var(--svg-color--8e6543, #8E6543);
  stop-opacity: 0;
}

.g9bzf2-1w {
  fill-rule: evenodd;
  d: path("M27.361 25.76v1.051l-2.619-.162a.358.358 0 0 1-.001-.715z");
}

.h-6n87bth {
  stop-color: var(--svg-color--a84540, #A84540);
}

.hknia-rwu {
  fill: var(--svg-color--1d1238, #1D1238);
  d: path("M8.141 24.285h6.781v.501H8.141z");
}

.hw3x87bxg {
  d: path("M21.821 17.58c-1.442 0-2.576 1.127-2.576 2.56v3.584h5.152V20.14c0-1.433-1.133-2.56-2.576-2.56");
}

.i234zr5bb {
  stop-color: var(--svg-color--ae796a, #AE796A);
}

.i9m24xbnn {
  stop-color: var(--svg-color--f9bb7c, #F9BB7C);
  stop-opacity: 0;
}

.iq-1bsb7s {
  fill-rule: evenodd;
  d: path("M4.892 25.836v-1.05l1.173.124a.378.378 0 0 1 .015.75z");
}

.j-db6kb8p {
  stop-color: var(--svg-color--d5322f, #D5322F);
}

.jlcs8ub8p {
  stop-color: var(--svg-color--8c5e55, #8C5E55);
}

.jmcmn2tah {
  d: path("M27.361 29.913H4.891V14.05l11.286-8.843l11.184 9.187z");
}

.josyhbbcc {
  stop-color: var(--svg-color--875956, #875956);
}

.k--2kgbfo {
  stop-color: var(--svg-color--363461, #363461);
}

.k2se42b6d {
  d: path("m22.876 11.443l-4.65.078a.411.411 0 0 0 .003.823l5.786.057z");
}

.k5us68bov {
  stop-color: var(--svg-color--de8c4c, #DE8C4C);
}

.kv15-1vjl {
  stop-color: var(--svg-color--82474f, #82474F);
  stop-opacity: 0;
}

.kw4rn-bvy {
  stop-color: var(--svg-color--db986a, #DB986A);
}

.le_q_-b3j {
  d: path("m13.886 10.214l-3.228.175l.739-.91h2.469a.367.367 0 0 1 .02.735");
}

.leu9f3p8r {
  stop-color: var(--svg-color--3b2249, #3B2249);
}

.mje4td9lu {
  stop-color: var(--svg-color--ab4d46, #AB4D46);
}

.mq5sflbrn {
  stop-color: var(--svg-color--ffbe7f, #FFBE7F);
  stop-opacity: 0;
}

.mt-6s8beo {
  stop-color: var(--svg-color--e8bc97, #E8BC97);
}

.n20kmrqgp {
  d: path("M6.929 24.182c-.09-.471-.05-.989.012-1.365a.454.454 0 0 1 .456-.37l8.288-.055a.477.477 0 0 1 .487.447c.021.424.013.842-.003 1.165a.48.48 0 0 1-.48.449l-8.315.066c-.212.002-.406-.13-.445-.337");
}

.n5-mfdbhl {
  stop-color: var(--svg-color--9b542b, #9B542B);
}

.n8s4uabpq {
  stop-color: var(--svg-color--926b50, #926B50);
}

.npvtk6bwu {
  stop-color: var(--svg-color--95605c, #95605C);
}

.ns11g_bru {
  stop-color: var(--svg-color--765150, #765150);
}

.o4ld_ebqr {
  stop-color: var(--svg-color--865955, #865955);
}

.olvjm8b_s {
  stop-color: var(--svg-color--82474f, #82474F);
}

.p81nog0zt {
  stop-color: var(--svg-color--f35b47, #F35B47);
  stop-opacity: 0;
}

.ph8qe-b3q {
  stop-color: var(--svg-color--391c42, #391C42);
}

.pnrdq1_ru {
  stop-color: var(--svg-color--e2692e, #E2692E);
}

.prq6w6vez {
  stop-color: var(--svg-color--dfa372, #DFA372);
}

.ps3vji8sb {
  stop-color: var(--svg-color--3e294d, #3E294D);
}

.pv7n3io0c {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
}

.q6y64jbmq {
  stop-color: var(--svg-color--cb8c5c, #CB8C5C);
}

.qxybjpb0z {
  stop-color: var(--svg-color--6c3a44, #6C3A44);
}

.rrzt1d-pe {
  stop-color: var(--svg-color--302b5b, #302B5B);
}

.rvxvvfb_b {
  stop-color: var(--svg-color--cd7d44, #CD7D44);
}

.s140eac2l {
  stop-color: var(--svg-color--ba5249, #BA5249);
  stop-opacity: 0;
}

.s18hfjbgv {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.782 21.155v8.312");
}

.s2t2-vb8g {
  d: path("m9.156 11.927l.79-.65l-.515-.633l-1.665 1.211l.984.178a.5.5 0 0 0 .406-.106");
}

.sgh_ghb0n {
  fill: var(--svg-color--1d1238, #1D1238);
  d: path("m8.148 20.977l6.52-1.115l.13.76l-6.65 1.116z");
}

.sgjwsvb6p {
  stop-color: var(--svg-color--ce8044, #CE8044);
}

.sjhtg-xeu {
  stop-color: var(--svg-color--372856, #372856);
}

.skdjsiuew {
  stop-color: var(--svg-color--925b35, #925B35);
}

.skv-xe6bz {
  stop-color: var(--svg-color--b5653b, #B5653B);
}

.tbf7krb3d {
  stop-color: var(--svg-color--a64f31, #A64F31);
}

.tg5ylwgwl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.398 5.613v.985a.1.1 0 0 0 .1.1h1.816a.1.1 0 0 1 .1.1V9.48");
}

.tim3_4bcp {
  stop-color: var(--svg-color--ff8739, #FF8739);
}

.tn5jawbxu {
  stop-color: var(--svg-color--dd8045, #DD8045);
}

.u0h_oitmh {
  stop-color: var(--svg-color--dfa372, #DFA372);
  stop-opacity: 0;
}

.uliagebas {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
  stop-opacity: 0;
}

.uuaff7f3s {
  stop-color: var(--svg-color--ba5249, #BA5249);
}

.v1iieqbzg {
  d: path("m25.655 19.217l-8.152 1.727a.465.465 0 0 0-.377.51a6.4 6.4 0 0 0 .293 1.2a.5.5 0 0 0 .577.323l8.099-1.707c.259-.054.43-.3.384-.56a21 21 0 0 0-.24-1.127a.494.494 0 0 0-.584-.366");
}

.vfrcjhz5y {
  stop-color: var(--svg-color--ffbe7f, #FFBE7F);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vuopvs98u {
  stop-color: var(--svg-color--363461, #363461);
  stop-opacity: 0;
}

.w5xxv7bof {
  d: path("M8.937 6.777v6.486c0 .325-.303.65-.606.65H5.398c-.304 0-.506-.325-.506-.65V5.786c0-.325.202-.542.505-.542h.972c.304 0 .506.217.506.542v.399c0 .028.022.05.05.05h1.406c.303 0 .606.217.606.542");
}

.wyry6cbrh {
  stop-color: var(--svg-color--a84540, #A84540);
  stop-opacity: 0;
}

.x-0itb8qp {
  fill: var(--svg-color--270e31, #270E31);
  d: path("M19.438 22.91v-.313l4.782-1.172v.438z");
}

.xd9iq1g7o {
  stop-color: var(--svg-color--f9bb7c, #F9BB7C);
}

.y2v_dxbqp {
  stop-color: var(--svg-color--3e294d, #3E294D);
  stop-opacity: 0;
}

.y4zdbibkp {
  stop-color: var(--svg-color--edbb99, #EDBB99);
}

.yc9ijacob {
  stop-color: var(--svg-color--df9051, #DF9051);
}

.yh009tbwt {
  d: path("M7.955 21.259a3.576 3.576 0 1 1 7.152 0v8.654H7.954z");
}

.z_h7t_gnx {
  stop-color: var(--svg-color--97695f, #97695F);
  stop-opacity: 0;
}

.zc8cbbcqr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m29.14 15.646l-11.963-9.51");
}

.zrz2f6bga {
  d: path("M6.677 13.879a.25.25 0 0 1-.09.233l-2.817 2.28a1 1 0 1 1-1.258-1.555L15.359 4.44A1 1 0 0 1 16 4.22a1 1 0 0 1 .64.222l3.492 2.826a.5.5 0 0 1 .186.388v.212a.5.5 0 0 0 .185.388l1.443 1.171a.5.5 0 0 0 .378.108l.317-.04a.5.5 0 0 1 .377.107l6.47 5.236a1 1 0 1 1-1.258 1.555l-12.136-9.82a.15.15 0 0 0-.188 0l-6.088 4.926a.25.25 0 0 1-.228.045l-.172-.051a.8.8 0 0 0-.721.138L6.953 13a.8.8 0 0 0-.296.755z");
}

</style>
