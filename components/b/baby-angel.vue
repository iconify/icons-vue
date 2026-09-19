<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUzBQxc)"><path fill="url(#iBAAyXb)" class="supagvb8e"/><path fill="url(#iXzKLxO)" class="supagvb8e"/><path fill="url(#iMgR3jc)" class="supagvb8e"/><path fill="url(#imaWdXc)" class="supagvb8e"/><path fill="url(#iE53qfd)" class="supagvb8e"/><path fill="url(#iV9G0zc)" class="supagvb8e"/></g><path fill="url(#i3fNjDd)" class="supagvb8e"/><path class="n55r6jbfn"/><path fill="url(#i5WXbjp)" class="m3509-fun"/><path fill="url(#i2xADqb)" class="m3509-fun"/><path fill="url(#iWPrc4b)" class="m3509-fun"/><path fill="url(#iXhITfc)" class="m3509-fun"/><g filter="url(#iK3J10c)"><path class="cb8d3wr7z"/><path fill="url(#i8MjDSb)" class="bfq3a8bij"/><path fill="url(#i6lWiWc)" class="bfq3a8bij"/><path fill="url(#ijstj6d)" class="bfq3a8bij"/></g><g filter="url(#iu2yu2A)"><path class="qkfc8pbqb"/><path fill="url(#iLeoLWc)" class="f9ktgbb3y"/><path fill="url(#iI5sZoL)" class="f9ktgbb3y"/><path fill="url(#iJ2pQrb)" class="f9ktgbb3y"/></g><g filter="url(#i9v4JHc)"><rect transform="matrix(-1 0 0 1 24.129 23.738)" class="ljzk3pb-v"/><rect fill="url(#ir52G6c)" transform="matrix(-1 0 0 1 24.129 23.738)" class="spx4avb5u"/></g><g filter="url(#iUigyCb)"><path class="kvq6_-e8h"/><path fill="url(#ishF73y)" class="k3o3btb6u"/><path fill="url(#il62gBM)" class="k3o3btb6u"/></g><g filter="url(#iEJAXqc)"><path class="p0z-iacrr"/><path fill="url(#ixjXyKa)" class="zz-7yrklx"/><path fill="url(#iS6Xqld)" class="zz-7yrklx"/></g><path fill="url(#iXS1URc)" class="zz-7yrklx"/><g filter="url(#iPA6Gkc)"><path class="a_m6jqbkr"/><path class="erpp2bb9q"/><path fill="url(#i5g2eCb)" class="w67ysfbnv"/></g><path fill="url(#iGtm0ze)" class="w67ysfbnv"/><g filter="url(#iZESbBb)"><rect fill="url(#ibi5ode)" class="w58rbbcmh"/><rect fill="url(#iOpFwlb)" class="w58rbbcmh"/></g><path fill="url(#iiPB6vb)" class="pm67p5-gs"/><path fill="url(#iP9ylnb)" class="pm67p5-gs"/><g filter="url(#iVZiPae)"><path class="yhrlv517c"/><path fill="url(#i7TJwlZ)" class="fvwj7vb8k"/></g><path fill="url(#iDtRuCo)" class="iqt-vab6o"/><path fill="url(#ieI7kVc)" class="iqt-vab6o"/><path fill="url(#iZyJh6b)" class="iqt-vab6o"/><g filter="url(#iwY03Ce)"><path fill="url(#iJPclec)" class="ub2upactf"/></g><g filter="url(#iWoknPb)"><path fill="url(#ioe0fBc)" class="hf2nr5hxd"/><path fill="url(#itPkswe)" class="hf2nr5hxd"/><path fill="url(#ips1Tjn)" class="hf2nr5hxd"/><path fill="url(#i9Udf6d)" class="hf2nr5hxd"/><path fill="url(#iNQ0aec)" class="hf2nr5hxd"/><path fill="url(#iDXnlUd)" class="hf2nr5hxd"/></g><g filter="url(#iXRl9tc)"><path stroke="url(#iIelKbb)" class="kdp379v0h"/></g><g filter="url(#imKvThd)"><path class="f19_knbti"/></g><path class="l78w_dbsg"/><path fill="url(#iTl4iTc)" class="zzscjleug"/><path fill="url(#ilar9be)" class="jztcgib3z"/><path class="yyays5b0g"/><g filter="url(#iMXoMKd)"><path class="s61kflb4y"/></g><g filter="url(#ii69Nab)"><path class="lx3sgn-4h"/></g><g filter="url(#infUcQd)"><path class="lszofku1s"/></g><g filter="url(#iLfUcHk)"><path class="fnwzmcc9b"/></g><g filter="url(#iV7jB6b)"><path fill="url(#im0TjOe)" class="ggisn9n_j"/></g><g filter="url(#iuoZ2dk)"><path class="wqd3gv-su"/><path fill="url(#iYKDsFc)" class="el0x9sroi"/><path fill="url(#ijoRykc)" class="el0x9sroi"/></g><g filter="url(#iCYVzVc)"><path class="cnudbhb1p"/></g><g filter="url(#ih939Uc)"><path fill="url(#i5diJie)" class="z0il7ccdr"/></g><g filter="url(#iOFxyjo)"><path class="zg57d7oou"/><path fill="url(#iXime4b)" class="aiu8iebwd"/></g><g filter="url(#i8HAxge)"><path fill="url(#iHHdetd)" class="sdknihi8y"/></g><g filter="url(#i60P3He)"><path fill="url(#ipMbtkc)" class="qunul038n"/></g><g filter="url(#imTRE2b)"><ellipse transform="rotate(-27.914 10.957 19.606)" class="r-2ing57c"/><ellipse fill="url(#i0sDFEb)" transform="rotate(-27.914 10.957 19.606)" class="hd_oom78x"/></g><defs><radialGradient id="iBAAyXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75003 3.6875 -9.72121 -1.97727 20.936 3.293)" gradientUnits="userSpaceOnUse"><stop class="j4e9jliyw"/><stop offset="1" class="t7aapjj0e"/></radialGradient><radialGradient id="iXzKLxO" cx="0" cy="0" r="1" gradientTransform="rotate(-57.45 10.963 -4.149)scale(5.22735 10.6403)" gradientUnits="userSpaceOnUse"><stop class="v_ro-mcce"/><stop offset="1" class="ak0e0gbla"/></radialGradient><radialGradient id="iMgR3jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 1.46875 -1.11569 1.02074 9.827 6.887)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="t82mlk1zf"/><stop offset="1" class="hrncwbz_t"/></radialGradient><radialGradient id="imaWdXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 -.98438 .58816 -.61616 10.327 7.34)" gradientUnits="userSpaceOnUse"><stop class="oxnp2k1qi"/><stop offset="1" class="ih62nvbvg"/></radialGradient><radialGradient id="iE53qfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 1.85939 -1.34213 -1.93987 23.265 7.684)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="i2to8tbny"/><stop offset="1" class="rr59_uoqr"/></radialGradient><radialGradient id="iV9G0zc" cx="0" cy="0" r="1" gradientTransform="rotate(144.605 10.248 6.892)scale(1.45673 1.05149)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ohd-ppblk"/><stop offset="1" class="c62dirbjk"/></radialGradient><radialGradient id="i3fNjDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93752 -7.271 18.54198 -4.94092 11.718 9.751)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="op4ic3bzn"/><stop offset="1" class="uoj15rbmy"/></radialGradient><radialGradient id="i2xADqb" cx="0" cy="0" r="1" gradientTransform="matrix(.6072 2.64774 -4.70572 1.07914 25.39 27.538)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="iWPrc4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.52434 .60868 -.33593 -.28939 26.855 28.04)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="i6lWiWc" cx="0" cy="0" r="1" gradientTransform="matrix(.76907 2.71875 -5.8088 1.64318 26.538 25.434)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="m63xmacvx"/><stop offset=".891" class="mm6hvvbia"/></radialGradient><radialGradient id="ijstj6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.66412 .625 -.34814 -.36993 28.395 25.95)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="iI5sZoL" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 2.71875 -6.83491 2.35687 27.733 23.34)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="m63xmacvx"/><stop offset=".922" class="ghrfdpdai"/></radialGradient><radialGradient id="iJ2pQrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80957 .625 -.33743 -.43707 29.996 23.855)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vc--wpv5i"/><stop offset="1" class="fr51zgblk"/></radialGradient><radialGradient id="ishF73y" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 1.73438 -1.37456 -.54486 8.812 28.512)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="y7rsoxb6i"/><stop offset="1" class="i8um3jglr"/></radialGradient><radialGradient id="il62gBM" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 -2.21094 5.39927 1.3355 6.765 30.137)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="bs3nz4btd"/><stop offset="1" class="qxhhvqurd"/></radialGradient><radialGradient id="ixjXyKa" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 2.25 -2.22312 -.80279 8.78 26.23)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="mjdwlzfcx"/><stop offset="1" class="cb_xa0byd"/></radialGradient><radialGradient id="iS6Xqld" cx="0" cy="0" r="1" gradientTransform="rotate(-69.661 23.023 9.986)scale(2.42119 7.08044)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="a-hxohb_j"/><stop offset="1" class="yi34m9bam"/></radialGradient><radialGradient id="iXS1URc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0827 3.1875 -5.20641 -1.76845 5.832 25.23)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="iGtm0ze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 3.46875 -6.65848 -2.33947 4.718 23.137)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="uh_-bgsil"/><stop offset=".986" class="s781d-sgv"/></radialGradient><radialGradient id="ibi5ode" cx="0" cy="0" r="1" gradientTransform="rotate(122.4 -2.432 16.414)scale(1.9246 3.13561)" gradientUnits="userSpaceOnUse"><stop class="uqd9t5bdt"/><stop offset="1" class="vsxpbmbdw"/></radialGradient><radialGradient id="iP9ylnb" cx="0" cy="0" r="1" gradientTransform="rotate(-157.686 5.682 9.806)scale(3.72167 4.84268)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="w_r7-9bim"/><stop offset="1" class="oybb58bnw"/></radialGradient><radialGradient id="i7TJwlZ" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.694 13.908)scale(1.86372)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="zv7ttxbjc"/><stop offset="1" class="gpp3aqbxg"/></radialGradient><radialGradient id="ieI7kVc" cx="0" cy="0" r="1" gradientTransform="rotate(90.949 2.941 22.081)scale(4.35504 4.17363)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="fm6dqtc6i"/><stop offset="1" class="d1mprq6ip"/></radialGradient><radialGradient id="iZyJh6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.57163 -1.81675 1.79276 1.55088 25.068 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="iw334hahu"/><stop offset=".883" class="v294fhb1o"/></radialGradient><radialGradient id="ioe0fBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.0613 -11.7232 0 21.314 14.59)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="r1lbydbys"/><stop offset="1" class="iyv92ybgd"/></radialGradient><radialGradient id="itPkswe" cx="0" cy="0" r="1" gradientTransform="matrix(2.94141 -3.84979 8.49916 6.49375 9.77 29.988)" gradientUnits="userSpaceOnUse"><stop class="fmlmf6b4u"/><stop offset="1" class="hhy8o7t0r"/></radialGradient><radialGradient id="ips1Tjn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.0856 14.2243 0 16 30.594)" gradientUnits="userSpaceOnUse"><stop class="ci9lecc-p"/><stop offset="1" class="pqn6fmb_j"/></radialGradient><radialGradient id="iNQ0aec" cx="0" cy="0" r="1" gradientTransform="matrix(1.32652 -2.81165 3.1562 1.48908 20.703 19.578)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="ht-7f4bgu"/><stop offset="1" class="e7g5x3bay"/></radialGradient><radialGradient id="iDXnlUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.21117 -2.68187 2.95153 1.33295 11.605 19.838)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="chhjzdbtk"/><stop offset="1" class="rbo5nsffk"/></radialGradient><radialGradient id="iIelKbb" cx="0" cy="0" r="1" gradientTransform="matrix(.8059 -1.02011 2.49861 1.97392 13.944 25.4)" gradientUnits="userSpaceOnUse"><stop class="jz-1qxb3p"/><stop offset="1" class="dk9521ecl"/></radialGradient><radialGradient id="iTl4iTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3121 -2.08704 0 19.852 20.357)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="r01x0bbde"/><stop offset="1" class="sk--2-b-a"/></radialGradient><radialGradient id="ilar9be" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3121 -2.08704 0 11.575 20.357)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="r01x0bbde"/><stop offset="1" class="sk--2-b-a"/></radialGradient><radialGradient id="iYKDsFc" cx="0" cy="0" r="1" gradientTransform="matrix(7.2178 -1.92373 1.60483 6.02127 12.309 8.734)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="yfecvtcdb"/><stop offset=".999" class="ncmwj9bfa"/></radialGradient><radialGradient id="ijoRykc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.764 11.036 .4)scale(6.20286 6.39506)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="vb0mv6bar"/><stop offset=".987" class="apprgee8k"/></radialGradient><radialGradient id="i5diJie" cx="0" cy="0" r="1" gradientTransform="rotate(117.715 1.651 16.046)scale(1.86503 2.81945)" gradientUnits="userSpaceOnUse"><stop offset=".084" class="p-1qhibxi"/><stop offset="1" class="q4myb4blf"/></radialGradient><radialGradient id="iXime4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.52757 -.67984 .93598 -.72633 19.333 20.015)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0sDFEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0176 -1.12388 1.35095 -.02115 10.923 20.322)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iUzBQxc" width="17.94" height="7.94" x="7.011" y="1.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.596078 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iK3J10c" width="7.412" height="2.194" x="20.982" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iu2yu2A" width="9.014" height="2.194" x="20.982" y="23.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.768627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="i9v4JHc" width="4.369" height="6.627" x="20.16" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.54902 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iUigyCb" width="6.273" height="2.439" x="4.645" y="27.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.541176 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iEJAXqc" width="7.813" height="2.494" x="3.105" y="25.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iPA6Gkc" width="9.414" height="2.494" x="1.504" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.694118 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iZESbBb" width="4.369" height="6.627" x="7.471" y="23.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.54902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iVZiPae" width="4.227" height="4.227" x="5.101" y="18.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".125"/></filter><filter id="iwY03Ce" width="4.342" height="4.342" x="22.577" y="18.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".125"/></filter><filter id="iWoknPb" width="21.552" height="23.993" x="5.849" y="5.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iXRl9tc" width="6.861" height="2.615" x="12.551" y="23.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".05"/></filter><filter id="imKvThd" width="6.46" height="2.215" x="12.752" y="23.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iMXoMKd" width="3.529" height="1.569" x="9.464" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.235294 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="ii69Nab" width="2.979" height=".969" x="9.665" y="15.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".1"/></filter><filter id="infUcQd" width="3.529" height="1.569" x="18.535" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.235294 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iLfUcHk" width="2.979" height=".969" x="18.935" y="15.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".1"/></filter><filter id="iV7jB6b" width="7.355" height="8.11" x="12.381" y="4.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".25"/></filter><filter id="iuoZ2dk" width="7.582" height="7.886" x="12.309" y="3.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.458824 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_320"/></filter><filter id="iCYVzVc" width="3.435" height="2.479" x="14.141" y="21.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".25"/></filter><filter id="ih939Uc" width="2.935" height="1.979" x="14.514" y="21.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".125"/></filter><filter id="iOFxyjo" width="1.535" height="1.329" x="18.309" y="18.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".05"/></filter><filter id="i8HAxge" width="1.517" height="1.568" x="20.348" y="19.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".1"/></filter><filter id="i60P3He" width="1.734" height="1.856" x="11.891" y="19.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".1"/></filter><filter id="imTRE2b" width="1.822" height="1.347" x="10.046" y="18.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_320" stdDeviation=".05"/></filter><linearGradient id="i5WXbjp" x1="24.585" x2="24.585" y1="30.188" y2="28.693" gradientUnits="userSpaceOnUse"><stop offset=".079" class="ja2ta5btn"/><stop offset="1" class="oci36vbzb"/></linearGradient><linearGradient id="iXhITfc" x1="24.436" x2="24.436" y1="27.926" y2="28.324" gradientUnits="userSpaceOnUse"><stop class="quz6sacji"/><stop offset="1" class="hw65_7bjg"/></linearGradient><linearGradient id="i8MjDSb" x1="25.518" x2="25.518" y1="27.926" y2="26.879" gradientUnits="userSpaceOnUse"><stop offset=".216" class="e6rsc3sik"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="iLeoLWc" x1="26.49" x2="26.49" y1="25.832" y2="24.785" gradientUnits="userSpaceOnUse"><stop offset=".216" class="rhghrobxp"/><stop offset="1" class="ki9dlqbnk"/></linearGradient><linearGradient id="ir52G6c" x1="0" x2=".958" y1="5.398" y2="5.398" gradientUnits="userSpaceOnUse"><stop class="lwh7ev7yo"/><stop offset="1" class="lesqr_bdp"/></linearGradient><linearGradient id="i5g2eCb" x1="6.461" x2="6.461" y1="23.738" y2="24.621" gradientUnits="userSpaceOnUse"><stop class="gjp7xwfce"/><stop offset="1" class="lo1zrhbvw"/></linearGradient><linearGradient id="iOpFwlb" x1="7.871" x2="9.124" y1="29.137" y2="29.137" gradientUnits="userSpaceOnUse"><stop class="gw5f7-xty"/><stop offset="1" class="v8imspx_m"/></linearGradient><linearGradient id="iiPB6vb" x1="4.608" x2="7.215" y1="20.602" y2="20.371" gradientUnits="userSpaceOnUse"><stop class="d8xp-vbup"/><stop offset="1" class="p-wzk38ah"/></linearGradient><linearGradient id="iDtRuCo" x1="27.101" x2="25.025" y1="18.266" y2="22.909" gradientUnits="userSpaceOnUse"><stop class="da366tb6r"/><stop offset="1" class="lw70zrunl"/></linearGradient><linearGradient id="iJPclec" x1="25.876" x2="26.178" y1="21.669" y2="18.828" gradientUnits="userSpaceOnUse"><stop offset=".302" class="kyej7mc7h"/><stop offset="1" class="g-qng6b1e"/></linearGradient><linearGradient id="i9Udf6d" x1="6.443" x2="12.326" y1="21.395" y2="21.395" gradientUnits="userSpaceOnUse"><stop class="xz-50o4by"/><stop offset="1" class="mu403ebre"/></linearGradient><linearGradient id="im0TjOe" x1="18.462" x2="15.412" y1="6.552" y2="11.855" gradientUnits="userSpaceOnUse"><stop class="ry3r2tbgs"/><stop offset="1" class="kyz4h9b7r"/></linearGradient><linearGradient id="iHHdetd" x1="21.622" x2="20.908" y1="19.946" y2="20.386" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipMbtkc" x1="13.267" x2="12.553" y1="19.946" y2="20.386" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baby-angel" /></template>
<style>
.a_m6jqbkr {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.a-hxohb_j {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
  stop-opacity: 0;
}

.aiu8iebwd {
  d: path("M19.707 19.167c.145.194-.157.43-.501.687s-.599.438-.743.244c-.145-.193.016-.558.36-.816s.74-.308.884-.115");
}

.ak0e0gbla {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
  stop-opacity: 0;
}

.apprgee8k {
  stop-color: var(--svg-color--c9983d, #C9983D);
}

.bfq3a8bij {
  d: path("M28.395 26.33a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.bs3nz4btd {
  stop-color: var(--svg-color--e7cbd8, #E7CBD8);
  stop-opacity: 0;
}

.c62dirbjk {
  stop-color: var(--svg-color--439fb2, #439FB2);
  stop-opacity: 0;
}

.cb_xa0byd {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
  stop-opacity: 0;
}

.cb8d3wr7z {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M28.395 26.33a.5.5 0 0 0-.499-.498h-6.814v2.094h5.717c.881 0 1.596-.714 1.596-1.595");
}

.chhjzdbtk {
  stop-color: var(--svg-color--f0953d, #F0953D);
}

.ci9lecc-p {
  stop-color: var(--svg-color--d87a77, #D87A77);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnudbhb1p {
  fill: var(--svg-color--f1902d, #F1902D);
  d: path("M15.86 23.6c.47 0 .89-.258 1.13-.647c.22-.356-.01-.831-.41-.831h-1.44c-.4 0-.64.486-.41.831c.24.4.66.648 1.13.648");
}

.d1mprq6ip {
  stop-color: var(--svg-color--d58651, #D58651);
}

.d8xp-vbup {
  stop-color: var(--svg-color--de8d27, #DE8D27);
}

.da366tb6r {
  stop-color: var(--svg-color--ffe13f, #FFE13F);
}

.dk9521ecl {
  stop-color: var(--svg-color--ffb74a, #FFB74A);
  stop-opacity: 0;
}

.e6rsc3sik {
  stop-color: var(--svg-color--c6bec8, #C6BEC8);
}

.e7g5x3bay {
  stop-color: var(--svg-color--ffba36, #FFBA36);
  stop-opacity: 0;
}

.el0x9sroi {
  d: path("M15.815 4.181A3.94 3.94 0 0 0 12.31 6.23a8 8 0 0 1 1.734-.203h.139c1.67 0 3.073 1.366 3.063 3.036a3 3 0 0 1-.747 1.965a.5.5 0 0 0 .526.812a3.93 3.93 0 0 0 2.667-3.728c.01-2.14-1.735-3.903-3.876-3.93");
}

.erpp2bb9q {
  fill: var(--svg-color--f1d2d6, #F1D2D6);
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.f19_knbti {
  fill: var(--svg-color--8a034f, #8A034F);
  d: path("M15.974 24.49c-1.02 0-1.976-.25-2.775-.676c-.276-.148-.57.166-.395.435a3.78 3.78 0 0 0 3.179 1.742c1.332 0 2.5-.695 3.18-1.742c.165-.26-.12-.574-.396-.435a6.05 6.05 0 0 1-2.793.676");
}

.f9ktgbb3y {
  d: path("M29.996 24.237a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.fm6dqtc6i {
  stop-color: var(--svg-color--d58651, #D58651);
  stop-opacity: 0;
}

.fmlmf6b4u {
  stop-color: var(--svg-color--d17c51, #D17C51);
}

.fnwzmcc9b {
  stroke: var(--svg-color--c45b41, #C45B41);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.565 16.158c-.545-.194-1.302-.332-2.28-.24");
}

.fr51zgblk {
  stop-color: var(--svg-color--f7f1f1, #F7F1F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvwj7vb8k {
  d: path("M7.214 22.466a1.864 1.864 0 1 0 0-3.728a1.864 1.864 0 0 0 0 3.728");
}

.g-qng6b1e {
  stop-color: var(--svg-color--ffd165, #FFD165);
}

.ggisn9n_j {
  d: path("M16.204 4.917c-1.36-.206-2.554.101-3.323 1.129a7.2 7.2 0 0 1 1.587.034l.124.017c1.503.208 2.507 1.889 2.29 3.39a2.74 2.74 0 0 1-.918 1.675a.455.455 0 0 0 .373.797A3.57 3.57 0 0 0 19.2 8.937c.275-1.925-1.074-3.728-2.997-4.02");
}

.ghrfdpdai {
  stop-color: var(--svg-color--a89bb4, #A89BB4);
}

.gjp7xwfce {
  stop-color: var(--svg-color--cab1a7, #CAB1A7);
}

.gpp3aqbxg {
  stop-color: var(--svg-color--ce791d, #CE791D);
}

.gw5f7-xty {
  stop-color: var(--svg-color--e7d1d9, #E7D1D9);
}

.hd_oom78x {
  cx: 10.957px;
  cy: 19.606px;
  rx: 0.886px;
  ry: 0.449px;
}

.hf2nr5hxd {
  d: path("M22.652 7.648a8.18 8.18 0 0 0-4.896-1.652h-3.512a8.18 8.18 0 0 0-4.897 1.652c-2.438 1.836-3.757 4.891-3.455 8.02l.828 7.484c.273 2.898 2.194 5.334 4.859 6.165a14.9 14.9 0 0 0 8.842 0c2.665-.83 4.586-3.267 4.858-6.165l.83-7.484c.3-3.129-1.018-6.184-3.457-8.02");
}

.hhy8o7t0r {
  stop-color: var(--svg-color--d17c51, #D17C51);
  stop-opacity: 0;
}

.hrncwbz_t {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
  stop-opacity: 0;
}

.ht-7f4bgu {
  stop-color: var(--svg-color--ffba36, #FFBA36);
}

.hw65_7bjg {
  stop-color: var(--svg-color--feeeec, #FEEEEC);
  stop-opacity: 0;
}

.i2to8tbny {
  stop-color: var(--svg-color--4997c1, #4997C1);
}

.i8um3jglr {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
  stop-opacity: 0;
}

.ih62nvbvg {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
  stop-opacity: 0;
}

.iqt-vab6o {
  d: path("M24.748 23.601a3 3 0 1 0 0-5.998a3 3 0 0 0 0 5.998");
}

.iw334hahu {
  stop-color: var(--svg-color--ffb61f, #FFB61F);
}

.iyv92ybgd {
  stop-color: var(--svg-color--fdab24, #FDAB24);
}

.j4e9jliyw {
  stop-color: var(--svg-color--4de2ff, #4DE2FF);
}

.ja2ta5btn {
  stop-color: var(--svg-color--9a84af, #9A84AF);
}

.jz-1qxb3p {
  stop-color: var(--svg-color--ffb74a, #FFB74A);
}

.jztcgib3z {
  d: path("M11.57 18.738a2.03 2.03 0 0 0-1.956 2.566h3.922c.046-.176.074-.351.074-.536a2.044 2.044 0 0 0-2.04-2.03");
}

.k3o3btb6u {
  d: path("M5.145 28.411c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.kdp379v0h {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.974 24.49c-1.02 0-1.976-.25-2.775-.676c-.276-.148-.57.166-.395.435a3.78 3.78 0 0 0 3.179 1.742c1.332 0 2.5-.695 3.18-1.742c.165-.26-.12-.574-.396-.435a6.05 6.05 0 0 1-2.793.676Z");
}

.ki9dlqbnk {
  stop-color: var(--svg-color--d4c7cd, #D4C7CD);
  stop-opacity: 0;
}

.kvq6_-e8h {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M5.145 28.411c0-.268.217-.485.485-.485h5.288v2.039h-4.22a1.554 1.554 0 0 1-1.553-1.554");
}

.kyej7mc7h {
  stop-color: var(--svg-color--ffc332, #FFC332);
}

.kyz4h9b7r {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
}

.l78w_dbsg {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.327 18.12a3.18 3.18 0 0 1 3.082 2.408a.624.624 0 0 1-.609.776h-5.075a.524.524 0 0 1-.517-.619a3.18 3.18 0 0 1 3.12-2.565m-9.228 0a3.18 3.18 0 0 0-3.083 2.408a.624.624 0 0 0 .61.776h5.075a.524.524 0 0 0 .516-.619A3.19 3.19 0 0 0 11.1 18.12");
}

.lesqr_bdp {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljzk3pb-v {
  width: 3.969px;
  height: 6.227px;
  fill: var(--svg-color--f7e1ed, #F7E1ED);
  rx: 1px;
}

.lo1zrhbvw {
  stop-color: var(--svg-color--f2d3d7, #F2D3D7);
  stop-opacity: 0;
}

.lszofku1s {
  stroke: var(--svg-color--c15231, #C15231);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M21.565 16.293c-.545-.194-1.302-.332-2.28-.24");
}

.lw70zrunl {
  stop-color: var(--svg-color--ffbd36, #FFBD36);
}

.lwh7ev7yo {
  stop-color: var(--svg-color--f6eff5, #F6EFF5);
}

.lx3sgn-4h {
  stroke: var(--svg-color--c45b41, #C45B41);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.015 16.206c.545-.194 1.301-.332 2.28-.24");
}

.m3509-fun {
  d: path("M26.856 28.411a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.m63xmacvx {
  stop-color: var(--svg-color--cebfd0, #CEBFD0);
  stop-opacity: 0;
}

.mjdwlzfcx {
  stop-color: var(--svg-color--cfb6bb, #CFB6BB);
}

.mm6hvvbia {
  stop-color: var(--svg-color--a797b5, #A797B5);
}

.mu403ebre {
  stop-color: var(--svg-color--eb992c, #EB992C);
  stop-opacity: 0;
}

.n55r6jbfn {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M26.856 28.411a.485.485 0 0 0-.486-.485h-5.288v2.039h4.22c.858 0 1.553-.696 1.553-1.554");
}

.ncmwj9bfa {
  stop-color: var(--svg-color--ffd937, #FFD937);
}

.oci36vbzb {
  stop-color: var(--svg-color--c4b7cf, #C4B7CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohd-ppblk {
  stop-color: var(--svg-color--439fb2, #439FB2);
}

.op4ic3bzn {
  stop-color: var(--svg-color--43acc0, #43ACC0);
  stop-opacity: 0;
}

.oxnp2k1qi {
  stop-color: var(--svg-color--47c2d5, #47C2D5);
}

.oybb58bnw {
  stop-color: var(--svg-color--ce9f45, #CE9F45);
}

.p-1qhibxi {
  stop-color: var(--svg-color--ffe245, #FFE245);
}

.p-wzk38ah {
  stop-color: var(--svg-color--cb773f, #CB773F);
}

.p0z-iacrr {
  fill: var(--svg-color--e7cbd7, #E7CBD7);
  d: path("M3.605 26.33c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm67p5-gs {
  d: path("M7.215 23.601a3 3 0 1 0 0-5.998a3 3 0 0 0 0 5.998");
}

.pqn6fmb_j {
  stop-color: var(--svg-color--d87a77, #D87A77);
  stop-opacity: 0;
}

.q4myb4blf {
  stop-color: var(--svg-color--f29624, #F29624);
}

.qkfc8pbqb {
  fill: var(--svg-color--fdedeb, #FDEDEB);
  d: path("M29.996 24.237a.5.5 0 0 0-.498-.499h-8.416v2.094h7.319c.88 0 1.595-.714 1.595-1.595");
}

.qunul038n {
  d: path("M13.425 20.53c0-.656-.534-1.094-.678-1.226l-.656.635l.404.822z");
}

.quz6sacji {
  stop-color: var(--svg-color--cfcacf, #CFCACF);
}

.qxhhvqurd {
  stop-color: var(--svg-color--bfa9ad, #BFA9AD);
}

.r-2ing57c {
  cx: 10.957px;
  cy: 19.606px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.886px;
  ry: 0.449px;
}

.r01x0bbde {
  stop-color: var(--svg-color--8f564f, #8F564F);
}

.r1lbydbys {
  stop-color: var(--svg-color--ffe944, #FFE944);
}

.rbo5nsffk {
  stop-color: var(--svg-color--f0953d, #F0953D);
  stop-opacity: 0;
}

.rhghrobxp {
  stop-color: var(--svg-color--d3c5cf, #D3C5CF);
}

.rr59_uoqr {
  stop-color: var(--svg-color--4997c1, #4997C1);
  stop-opacity: 0;
}

.ry3r2tbgs {
  stop-color: var(--svg-color--e07f05, #E07F05);
}

.s61kflb4y {
  stroke: var(--svg-color--c15231, #C15231);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M9.964 16.293c.545-.194 1.301-.332 2.28-.24");
}

.s781d-sgv {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
}

.sdknihi8y {
  d: path("M21.665 20.501a1.9 1.9 0 0 0-.526-1.053l-.591.65l.267.518z");
}

.sk--2-b-a {
  stop-color: var(--svg-color--86534b, #86534B);
}

.spx4avb5u {
  width: 3.969px;
  height: 6.227px;
  rx: 1px;
}

.supagvb8e {
  d: path("M15.972 3.511c2.16 0 4.26.37 5.75 1.01c1.25.54 1.72 1.12 1.72 1.36s-.47.82-1.72 1.36c-1.49.64-3.58 1.01-5.75 1.01s-4.26-.36-5.74-1c-1.26-.54-1.72-1.13-1.72-1.37s.47-.82 1.72-1.36c1.48-.64 3.58-1.01 5.74-1.01m0-1.5c-4.95 0-8.96 1.73-8.96 3.87s4.01 3.87 8.97 3.87s8.97-1.73 8.97-3.87s-4.02-3.87-8.98-3.87");
}

.t7aapjj0e {
  stop-color: var(--svg-color--33aed4, #33AED4);
}

.t82mlk1zf {
  stop-color: var(--svg-color--5bbfd1, #5BBFD1);
}

.ub2upactf {
  d: path("M24.748 22.523a1.92 1.92 0 1 0 0-3.842a1.92 1.92 0 0 0 0 3.842");
}

.uh_-bgsil {
  stop-color: var(--svg-color--b0a1bb, #B0A1BB);
  stop-opacity: 0;
}

.uoj15rbmy {
  stop-color: var(--svg-color--43acc0, #43ACC0);
}

.uqd9t5bdt {
  stop-color: var(--svg-color--d7b5ca, #D7B5CA);
}

.v_ro-mcce {
  stop-color: var(--svg-color--3d8db9, #3D8DB9);
}

.v294fhb1o {
  stop-color: var(--svg-color--ffb61f, #FFB61F);
  stop-opacity: 0;
}

.v8imspx_m {
  stop-color: var(--svg-color--dac4cc, #DAC4CC);
  stop-opacity: 0;
}

.vb0mv6bar {
  stop-color: var(--svg-color--c9983d, #C9983D);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vsxpbmbdw {
  stop-color: var(--svg-color--dcbdc9, #DCBDC9);
}

.w_r7-9bim {
  stop-color: var(--svg-color--ce9f45, #CE9F45);
  stop-opacity: 0;
}

.w58rbbcmh {
  width: 3.969px;
  height: 6.227px;
  x: 7.871px;
  y: 23.738px;
  rx: 1px;
}

.w67ysfbnv {
  d: path("M2.004 24.237c0-.275.223-.499.498-.499h8.416v2.094H3.599a1.595 1.595 0 0 1-1.595-1.595");
}

.wqd3gv-su {
  fill: var(--svg-color--e99628, #E99628);
  d: path("M15.815 4.181A3.94 3.94 0 0 0 12.31 6.23a8 8 0 0 1 1.734-.203h.139c1.67 0 3.073 1.366 3.063 3.036a3 3 0 0 1-.747 1.965a.5.5 0 0 0 .526.812a3.93 3.93 0 0 0 2.667-3.728c.01-2.14-1.735-3.903-3.876-3.93");
}

.xz-50o4by {
  stop-color: var(--svg-color--eb992c, #EB992C);
}

.y7rsoxb6i {
  stop-color: var(--svg-color--af9aba, #AF9ABA);
}

.yfecvtcdb {
  stop-color: var(--svg-color--ffd937, #FFD937);
  stop-opacity: 0;
}

.yhrlv517c {
  fill: var(--svg-color--d78125, #D78125);
  d: path("M7.214 22.466a1.864 1.864 0 1 0 0-3.728a1.864 1.864 0 0 0 0 3.728");
}

.yi34m9bam {
  stop-color: var(--svg-color--d3b6b4, #D3B6B4);
}

.yyays5b0g {
  fill: var(--svg-color--000, #000);
  d: path("M18.694 20.768c0-.646.517-1.162 1.163-1.162s1.163.516 1.163 1.162c0 .194-.046.379-.13.535h-2.057a1.05 1.05 0 0 1-.139-.535m-5.961 0c0-.646-.517-1.162-1.163-1.162s-1.162.516-1.162 1.162c0 .194.046.379.129.536h2.058c.083-.157.138-.342.138-.536");
}

.z0il7ccdr {
  d: path("M15.984 23.278c.47 0 .89-.26 1.13-.648c.22-.356-.01-.831-.41-.831h-1.44c-.4 0-.64.486-.41.831c.24.4.66.648 1.13.648");
}

.zg57d7oou {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.707 19.167c.145.194-.157.43-.501.687s-.599.438-.743.244c-.145-.193.016-.558.36-.816s.74-.308.884-.115");
}

.zv7ttxbjc {
  stop-color: var(--svg-color--ce791d, #CE791D);
  stop-opacity: 0;
}

.zz-7yrklx {
  d: path("M3.605 26.33c0-.275.224-.498.499-.498h6.814v2.094H5.201a1.595 1.595 0 0 1-1.596-1.595");
}

.zzscjleug {
  d: path("M19.857 18.738a2.03 2.03 0 0 1 1.956 2.566h-3.922a2 2 0 0 1-.074-.536c0-1.116.914-2.03 2.04-2.03");
}

</style>
