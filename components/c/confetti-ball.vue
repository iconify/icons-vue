<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ou6t5ub5m"/><path fill="url(#iGXg35I)" class="n78g2i65a"/><path fill="url(#icX5U0b)" class="n78g2i65a"/><path fill="url(#iyCaZad)" class="n78g2i65a"/><g filter="url(#i5Is9lc)"><path class="q33e-4b9l"/><path fill="url(#i6dBkze)" class="bbyt42ohh"/><path fill="url(#i0QIvre)" class="bbyt42ohh"/></g><g filter="url(#ijcYUMb)"><ellipse stroke="url(#iJErPrb)" transform="scale(-1 1)rotate(45 -31.422 -18.36)" class="z1h6bqbtn"/></g><ellipse fill="url(#ik0frHW)" transform="scale(-1 1)rotate(45 -31.422 -18.36)" class="j4jya2bym"/><path clip-rule="evenodd" class="i3ejgbcsq"/><path fill="url(#iMUD11c)" clip-rule="evenodd" class="wibulobyi"/><path fill="url(#ifHJVUm)" clip-rule="evenodd" class="n8yc6lb8y"/><path fill="url(#iwpLlxe)" clip-rule="evenodd" class="n8yc6lb8y"/><path fill="url(#iGiC9ie)" clip-rule="evenodd" class="n8yc6lb8y"/><path fill="url(#i7dlejc)" clip-rule="evenodd" class="n8yc6lb8y"/><circle fill="url(#idbfa8G)" class="rt30btr2l"/><circle fill="url(#ibBboub)" class="l_mn324yd"/><circle fill="url(#ieemcwd)" class="eqz78fb9v"/><circle fill="url(#ikhogAd)" class="zmc0w_b6y"/><circle fill="url(#iEzNSUc)" class="pzr0gxnai"/><circle fill="url(#iwyicZb)" class="pzr0gxnai"/><g filter="url(#ihKwHDb)"><ellipse stroke="url(#iHnAMHc)" transform="rotate(45 9.687 16.842)" class="itqfcih7v"/></g><ellipse fill="url(#ifKnZDb)" transform="rotate(45 9.687 16.842)" class="cd4bilb_f"/><g filter="url(#iEyn4xi)"><path class="o2-ghvepq"/><path fill="url(#iYaFZqb)" class="qyaknltzb"/><path fill="url(#ik1fFQc)" class="qyaknltzb"/><path fill="url(#iohmHZc)" class="qyaknltzb"/></g><path class="v-ys2v-pd"/><path fill="url(#ieu9FHc)" class="zt1awvtgj"/><path fill="url(#i26pYIe)" class="zt1awvtgj"/><path fill="url(#ih8ZaPe)" class="zt1awvtgj"/><g filter="url(#iiqI4Gb)"><path class="gzmkctbaw"/></g><g filter="url(#iEc6L6I)"><path class="wpwnbokgv"/><path fill="url(#igEOQNy)" class="w1j5cub_o"/></g><path fill="url(#iJwcele)" class="w1j5cub_o"/><g filter="url(#iTZqhId)"><path stroke="url(#ivHTFEI)" class="i-v1yh62k"/></g><path class="kstaf_nil"/><path fill="url(#ixfKuse)" class="vjn09nwef"/><path fill="url(#i9XMrse)" class="vjn09nwef"/><path fill="url(#iDxMhge)" class="iz30dy80y"/><g filter="url(#iwr6isb)"><path stroke="url(#ieCEGUc)" class="wdnp9-ozl"/></g><g filter="url(#iTt0QMc)"><path stroke="url(#ilwgmFb)" class="cskfwdb9x"/></g><defs><radialGradient id="iGXg35I" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 -5.3125 3.85554 -3.53803 12.5 13.357)" gradientUnits="userSpaceOnUse"><stop class="muari8w8u"/><stop offset="1" class="sl9xzjbti"/></radialGradient><radialGradient id="icX5U0b" cx="0" cy="0" r="1" gradientTransform="rotate(61.118 -4.788 9.322)scale(13.4572 13.5847)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="hx1j4xz2n"/><stop offset="1" class="eo07ur6bn"/></radialGradient><radialGradient id="iyCaZad" cx="0" cy="0" r="1" gradientTransform="matrix(-9.16262 .50008 -.50085 -9.17683 11.062 15.857)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="wsgdl5_-l"/><stop offset="1" class="x3o31dnkz"/></radialGradient><radialGradient id="i6dBkze" cx="0" cy="0" r="1" gradientTransform="matrix(5.02786 -5.54799 4.62598 4.1923 25.324 16.543)" gradientUnits="userSpaceOnUse"><stop class="zc3_q-b7f"/><stop offset="1" class="am4rv9b2r"/></radialGradient><radialGradient id="i0QIvre" cx="0" cy="0" r="1" gradientTransform="rotate(27.79 -13.624 41.21)scale(3.03077 3.03547)" gradientUnits="userSpaceOnUse"><stop class="yl-cus5ut"/><stop offset="1" class="xnhz5xbwr"/></radialGradient><radialGradient id="iGiC9ie" cx="0" cy="0" r="1" gradientTransform="matrix(-2.78122 4.87501 -3.15863 -1.80202 20.25 15.482)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="hu_wxl6jl"/><stop offset="1" class="axhg604dr"/></radialGradient><radialGradient id="i7dlejc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.27433 -1.29741 1.26939 -6.13881 21.792 18.662)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="nglplte4m"/><stop offset=".95" class="g8g2wws_a"/></radialGradient><radialGradient id="idbfa8G" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.15626 -1.15626 -1 16.5 28.7)" gradientUnits="userSpaceOnUse"><stop class="vz0gmorja"/><stop offset="1" class="d5mctxbxl"/></radialGradient><radialGradient id="ibBboub" cx="0" cy="0" r="1" gradientTransform="rotate(140.042 5.167 15.798)scale(1.28272)" gradientUnits="userSpaceOnUse"><stop class="q60ztzb5t"/><stop offset="1" class="tqugr9boy"/></radialGradient><radialGradient id="ieemcwd" cx="0" cy="0" r="1" gradientTransform="rotate(144.498 7.284 17.589)scale(1.43947)" gradientUnits="userSpaceOnUse"><stop class="phh-j81_m"/><stop offset="1" class="q9ks04bqh"/></radialGradient><radialGradient id="ikhogAd" cx="0" cy="0" r="1" gradientTransform="rotate(-96.843 15.476 5.256)scale(1.18028)" gradientUnits="userSpaceOnUse"><stop class="aa5it0bnr"/><stop offset="1" class="z4e-h3vsi"/></radialGradient><radialGradient id="iEzNSUc" cx="0" cy="0" r="1" gradientTransform="rotate(138.621 -.427 15.147)scale(.87458)" gradientUnits="userSpaceOnUse"><stop class="t-yyynn7p"/><stop offset="1" class="cyz68y1vj"/></radialGradient><radialGradient id="iwyicZb" cx="0" cy="0" r="1" gradientTransform="rotate(-25.755 63.467 -5.608)scale(.98886)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="l38slfb_y"/><stop offset="1" class="xipw8g_9r"/></radialGradient><radialGradient id="ik1fFQc" cx="0" cy="0" r="1" gradientTransform="matrix(5.27332 -.54085 1.15713 11.28202 4.22 19.985)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="paum20bxu"/><stop offset="1" class="q76c0pj4r"/></radialGradient><radialGradient id="iohmHZc" cx="0" cy="0" r="1" gradientTransform="rotate(16.44 -56.427 29.25)scale(1.50961 3.19917)" gradientUnits="userSpaceOnUse"><stop class="bwzjo-uyy"/><stop offset="1" class="ebf2o976p"/></radialGradient><radialGradient id="ieu9FHc" cx="0" cy="0" r="1" gradientTransform="rotate(63.941 -7.753 13.63)scale(6.71021 1.69109)" gradientUnits="userSpaceOnUse"><stop class="jg3nrd4fx"/><stop offset="1" class="bahlzmnxn"/></radialGradient><radialGradient id="i26pYIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.30913 6.36156 -2.65138 -.12884 16.084 17.3)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="jg3nrd4fx"/><stop offset="1" class="bahlzmnxn"/></radialGradient><radialGradient id="ih8ZaPe" cx="0" cy="0" r="1" gradientTransform="rotate(-83.904 18.68 4.332)scale(3.75316 1.62491)" gradientUnits="userSpaceOnUse"><stop class="jg3nrd4fx"/><stop offset="1" class="bahlzmnxn"/></radialGradient><radialGradient id="iJwcele" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48988 .40624 -1.33533 -4.89726 27.177 24.826)" gradientUnits="userSpaceOnUse"><stop class="a6kc4fyip"/><stop offset="1" class="gglstv0xj"/></radialGradient><radialGradient id="ixfKuse" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.01562 -3.33143 .82005 18.921 19.888)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="l6yizirth"/><stop offset="1" class="p936r3b5j"/></radialGradient><radialGradient id="i9XMrse" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35316 .71876 -1.01125 -3.31076 20.14 20.326)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="p936r3b5j"/><stop offset="1" class="l6yizirth"/></radialGradient><radialGradient id="iDxMhge" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -1.53125 1.25877 -.0578 19.015 18.787)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="z2yf7b4br"/><stop offset="1" class="n6499sb3s"/></radialGradient><linearGradient id="iJErPrb" x1="-.892" x2="5.764" y1="5.106" y2="6.111" gradientUnits="userSpaceOnUse"><stop class="f81834b3v"/><stop offset="1" class="qxg7idzly"/></linearGradient><linearGradient id="ik0frHW" x1=".183" x2="2.519" y1="2.048" y2="12.816" gradientUnits="userSpaceOnUse"><stop class="gtiz2_tnj"/><stop offset="1" class="d1iu6icdp"/></linearGradient><linearGradient id="iMUD11c" x1="11.812" x2="13.187" y1="21.982" y2="27.17" gradientUnits="userSpaceOnUse"><stop class="auhda0btn"/><stop offset="1" class="pe1b83bwr"/></linearGradient><linearGradient id="ifHJVUm" x1="21.999" x2="16.999" y1="15.92" y2="21.757" gradientUnits="userSpaceOnUse"><stop offset=".253" class="nlnijlnvz"/><stop offset="1" class="ytexaxy1f"/></linearGradient><linearGradient id="iwpLlxe" x1="23.624" x2="22.593" y1="15.138" y2="16.013" gradientUnits="userSpaceOnUse"><stop class="watehllxo"/><stop offset="1" class="zb0grjbzu"/></linearGradient><linearGradient id="iHnAMHc" x1="6.276" x2="12.932" y1="15.539" y2="16.544" gradientUnits="userSpaceOnUse"><stop class="u7a9k0p9i"/><stop offset="1" class="nwe8ahptq"/></linearGradient><linearGradient id="ifKnZDb" x1="9.687" x2="9.687" y1="10.433" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="u-ut8cccc"/><stop offset="1" class="vbk4lwwtg"/></linearGradient><linearGradient id="iYaFZqb" x1="4.238" x2="6.042" y1="28.274" y2="26.613" gradientUnits="userSpaceOnUse"><stop class="vk-6y3skm"/><stop offset="1" class="ea84kxhyb"/></linearGradient><linearGradient id="igEOQNy" x1="26.687" x2="25.27" y1="17.17" y2="19.232" gradientUnits="userSpaceOnUse"><stop class="dxd9kmb2g"/><stop offset="1" class="qx2djx8va"/></linearGradient><linearGradient id="ivHTFEI" x1="26.484" x2="25.616" y1="26.42" y2="19.513" gradientUnits="userSpaceOnUse"><stop class="uhl03ccti"/><stop offset="1" class="wyvizzypi"/></linearGradient><linearGradient id="ieCEGUc" x1="17.843" x2="18.037" y1="16.782" y2="19.513" gradientUnits="userSpaceOnUse"><stop class="ebor5lvzh"/><stop offset="1" class="mipal1txk"/></linearGradient><linearGradient id="ilwgmFb" x1="22.687" x2="20.347" y1="15.451" y2="19.89" gradientUnits="userSpaceOnUse"><stop class="ebor5lvzh"/><stop offset="1" class="mipal1txk"/></linearGradient><filter id="i5Is9lc" width="13.115" height="12.94" x="16.728" y="9.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.698039 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_599"/></filter><filter id="ijcYUMb" width="10.64" height="10.64" x="16.865" y="11.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".1"/></filter><filter id="ihKwHDb" width="10.24" height="10.24" x="4.567" y="11.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".05"/></filter><filter id="iEyn4xi" width="5.279" height="12.758" x="3.937" y="15.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.054902 0 0 0 0 0.462745 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_599"/></filter><filter id="iiqI4Gb" width="2.506" height="4.825" x="13.871" y="19.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".3"/></filter><filter id="iEc6L6I" width="4.114" height="11.162" x="23.363" y="16.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.329412 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_599"/></filter><filter id="iTZqhId" width="3.636" height="8.806" x="23.798" y="18.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".325"/></filter><filter id="iwr6isb" width="4.169" height="4.422" x="16.014" y="16.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".375"/></filter><filter id="iTt0QMc" width="4.969" height="5.813" x="18.906" y="14.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_599" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:confetti-ball" /></template>
<style>
.a6kc4fyip {
  stop-color: var(--svg-color--4bdcff, #4BDCFF);
}

.aa5it0bnr {
  stop-color: var(--svg-color--d48d3b, #D48D3B);
}

.am4rv9b2r {
  stop-color: var(--svg-color--ffe76d, #FFE76D);
  stop-opacity: 0;
}

.auhda0btn {
  stop-color: var(--svg-color--c9136c, #C9136C);
}

.axhg604dr {
  stop-color: var(--svg-color--3165cf, #3165CF);
}

.bahlzmnxn {
  stop-color: var(--svg-color--a80963, #A80963);
  stop-opacity: 0;
}

.bbyt42ohh {
  d: path("m17.126 12.367l-.002-.002l.013-.023q.061-.126.146-.233a6.836 6.836 0 0 1 12.56 3.738c0 2.429-1.248 4.657-3.156 5.87c-1.208.809-4.084-.538-6.562-3.016c-2.364-2.364-3.592-5.043-3-6.334");
}

.bwzjo-uyy {
  stop-color: var(--svg-color--1569a5, #1569A5);
}

.cd4bilb_f {
  cx: 9.687px;
  cy: 16.842px;
  rx: 2.519px;
  ry: 6.408px;
}

.cskfwdb9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M22.874 15.45c-.291.688-1.243 2.738-2.968 3.813");
}

.cyz68y1vj {
  stop-color: var(--svg-color--e5a437, #E5A437);
}

.d1iu6icdp {
  stop-color: var(--svg-color--4d2c30, #4D2C30);
}

.d5mctxbxl {
  stop-color: var(--svg-color--2d64cf, #2D64CF);
}

.dxd9kmb2g {
  stop-color: var(--svg-color--184e8c, #184E8C);
}

.ea84kxhyb {
  stop-color: var(--svg-color--3067d9, #3067D9);
  stop-opacity: 0;
}

.ebf2o976p {
  stop-color: var(--svg-color--1569a5, #1569A5);
  stop-opacity: 0;
}

.ebor5lvzh {
  stop-color: var(--svg-color--46b4e2, #46B4E2);
}

.eo07ur6bn {
  stop-color: var(--svg-color--b9706d, #B9706D);
}

.eqz78fb9v {
  cx: 22.875px;
  cy: 27.92px;
  r: 0.906px;
}

.f81834b3v {
  stop-color: var(--svg-color--ecb43e, #ECB43E);
}

.ft5dv1b6b {
  fill: none;
}

.g8g2wws_a {
  stop-color: var(--svg-color--2471ad, #2471AD);
}

.gglstv0xj {
  stop-color: var(--svg-color--4bdcff, #4BDCFF);
  stop-opacity: 0;
}

.gtiz2_tnj {
  stop-color: var(--svg-color--572943, #572943);
}

.gzmkctbaw {
  stroke: var(--svg-color--ff5cac, #FF5CAC);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.671 20.67v1.68c0 .387.15.76.419 1.039l.487.506");
}

.hu_wxl6jl {
  stop-color: var(--svg-color--3165cf, #3165CF);
  stop-opacity: 0;
}

.hx1j4xz2n {
  stop-color: var(--svg-color--b9706d, #B9706D);
  stop-opacity: 0;
}

.i-v1yh62k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.421 19.513c-.692 1.146-1.45 4.132 1.063 6.907");
}

.i3ejgbcsq {
  fill: var(--svg-color--fc28a2, #FC28A2);
  fill-rule: evenodd;
  d: path("M10.885 22.864a1 1 0 0 1 1.296.566c.432 1.105 1.206 3.882-.793 6.367a1 1 0 0 1-1.558-1.254c1.3-1.616.847-3.467.488-4.383a1 1 0 0 1 .567-1.296");
}

.itqfcih7v {
  cx: 9.687px;
  cy: 16.842px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  rx: 2.519px;
  ry: 6.408px;
}

.iz30dy80y {
  d: path("M20.092 17.455c-.454-1.104-1.602-1.472-2.508-1.266a2.06 2.06 0 0 0-1.304.909a2.05 2.05 0 0 0-.293 1.228h1.742a.35.35 0 0 1 .08-.28c.339-.38.804.092.691.497c.355-.16 1.175-.659 1.592-1.088");
}

.j4jya2bym {
  rx: 2.519px;
  ry: 6.408px;
}

.jg3nrd4fx {
  stop-color: var(--svg-color--a80963, #A80963);
}

.kstaf_nil {
  fill: var(--svg-color--2a82d3, #2A82D3);
  d: path("m20.257 19.66l-.097.063l-.045.172c-.173.61-.45 1.178-.723 1.521a.9.9 0 0 1-1.482-1.014l-.028-.003c.507-.018 1.666-.296 2.301-.698z");
}

.l_mn324yd {
  cx: 18.937px;
  cy: 24.92px;
  r: 0.906px;
}

.l38slfb_y {
  stop-color: var(--svg-color--eb9530, #EB9530);
  stop-opacity: 0;
}

.l6yizirth {
  stop-color: var(--svg-color--1e58a8, #1E58A8);
}

.mipal1txk {
  stop-color: var(--svg-color--46b4e2, #46B4E2);
  stop-opacity: 0;
}

.muari8w8u {
  stop-color: var(--svg-color--ffe94c, #FFE94C);
}

.n6499sb3s {
  stop-color: var(--svg-color--3258a2, #3258A2);
  stop-opacity: 0;
}

.n78g2i65a {
  d: path("m14.617 12.367l.002-.002l-.014-.023a1.2 1.2 0 0 0-.145-.233A6.836 6.836 0 0 0 1.9 15.847c0 2.429 1.288 4.55 3.197 5.763c1.208.81 4.034-.43 6.512-2.91c2.363-2.363 3.6-5.042 3.008-6.333");
}

.n8yc6lb8y {
  fill-rule: evenodd;
  d: path("M22.854 14.546a.9.9 0 0 1 .473 1.182c-.797 1.856-1.976 3.231-3.167 3.995l-.045.172c-.173.61-.45 1.178-.723 1.521a.9.9 0 0 1-1.482-1.014a2 2 0 0 1-.267-.039c-.762-.156-1.325-.69-1.554-1.472c-.19-.647-.13-1.277.191-1.793c.31-.501.806-.796 1.304-.91c.906-.205 2.054.163 2.508 1.267c.57-.588 1.135-1.4 1.58-2.437a.9.9 0 0 1 1.182-.472m-5.045 3.5c.339-.38.804.092.691.497c-.477.348-.977-.135-.69-.496");
}

.nglplte4m {
  stop-color: var(--svg-color--2471ad, #2471AD);
  stop-opacity: 0;
}

.nlnijlnvz {
  stop-color: var(--svg-color--1da2cd, #1DA2CD);
}

.nwe8ahptq {
  stop-color: var(--svg-color--976061, #976061);
}

.o2-ghvepq {
  fill: var(--svg-color--24a4dc, #24A4DC);
  d: path("M6.281 16.965c.406-.567.887-1.145 1.433-1.71c.174.355.344.748.5 1.164c.431 1.153.796 2.591.847 4.091c.06 1.734-.514 3.305-1.227 4.54c-.711 1.233-1.598 2.199-2.268 2.74a1 1 0 0 1-1.258-1.554c.476-.385 1.203-1.16 1.793-2.184c.589-1.02 1.004-2.221.962-3.473c-.043-1.234-.347-2.455-.723-3.46z");
}

.ou6t5ub5m {
  fill: var(--svg-color--f6bf3f, #F6BF3F);
  d: path("m14.617 12.367l.002-.002l-.014-.023a1.2 1.2 0 0 0-.145-.233A6.836 6.836 0 0 0 1.9 15.847c0 2.429 1.288 4.55 3.197 5.763c1.208.81 4.034-.43 6.512-2.91c2.363-2.363 3.6-5.042 3.008-6.333");
}

.p936r3b5j {
  stop-color: var(--svg-color--1e58a8, #1E58A8);
  stop-opacity: 0;
}

.paum20bxu {
  stop-color: var(--svg-color--47cefa, #47CEFA);
  stop-opacity: 0;
}

.pe1b83bwr {
  stop-color: var(--svg-color--c9136c, #C9136C);
  stop-opacity: 0;
}

.phh-j81_m {
  stop-color: var(--svg-color--f7c851, #F7C851);
}

.pzr0gxnai {
  cx: 8.948px;
  cy: 26.899px;
  r: 0.739px;
}

.q33e-4b9l {
  fill: var(--svg-color--f7cc36, #F7CC36);
  d: path("m17.126 12.367l-.002-.002l.013-.023q.061-.126.146-.233a6.836 6.836 0 0 1 12.56 3.738c0 2.429-1.248 4.657-3.156 5.87c-1.208.809-4.084-.538-6.562-3.016c-2.364-2.364-3.592-5.043-3-6.334");
}

.q60ztzb5t {
  stop-color: var(--svg-color--ff48a3, #FF48A3);
}

.q76c0pj4r {
  stop-color: var(--svg-color--47cefa, #47CEFA);
}

.q9ks04bqh {
  stop-color: var(--svg-color--d97654, #D97654);
}

.qx2djx8va {
  stop-color: var(--svg-color--184e8c, #184E8C);
  stop-opacity: 0;
}

.qxg7idzly {
  stop-color: var(--svg-color--925960, #925960);
}

.qyaknltzb {
  d: path("M6.281 16.965c.406-.567.887-1.145 1.433-1.71c.174.355.344.748.5 1.164c.431 1.153.796 2.591.847 4.091c.06 1.734-.514 3.305-1.227 4.54c-.711 1.233-1.598 2.199-2.268 2.74a1 1 0 0 1-1.258-1.554c.476-.385 1.203-1.16 1.793-2.184c.589-1.02 1.004-2.221.962-3.473c-.043-1.234-.347-2.455-.723-3.46z");
}

.rt30btr2l {
  cx: 15.953px;
  cy: 28.951px;
  r: 0.906px;
}

.sl9xzjbti {
  stop-color: var(--svg-color--ffe94c, #FFE94C);
  stop-opacity: 0;
}

.t-yyynn7p {
  stop-color: var(--svg-color--f8ac4b, #F8AC4B);
}

.tqugr9boy {
  stop-color: var(--svg-color--db1d93, #DB1D93);
}

.u-ut8cccc {
  stop-color: var(--svg-color--5e2b40, #5E2B40);
}

.u7a9k0p9i {
  stop-color: var(--svg-color--eabe3f, #EABE3F);
}

.uhl03ccti {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
}

.v-ys2v-pd {
  fill: var(--svg-color--fa3f99, #FA3F99);
  d: path("m7.898 15.068l.008-.008a16 16 0 0 1 1.563-1.372c.145.34.35.781.594 1.236c.336.628.71 1.218 1.063 1.6c.223.242.418.275 1.034.269l.08-.001c.584-.008 1.573-.02 2.404.827c.842.828.814 1.78.797 2.362q-.004.112-.004.204v2.138a.5.5 0 0 0 .149.356l.631.622a1 1 0 0 1-1.404 1.425c-.69-.613-1.39-1.374-1.37-2.597l-.006-1.944c0-.094.002-.186.003-.266v-.008c.001-.086.003-.159.002-.229c0-.14-.006-.234-.019-.309a.53.53 0 0 0-.184-.33l-.01-.01l-.01-.01c-.204-.211-.382-.237-1.04-.23h-.028c-.618.006-1.64.016-2.496-.915c-.524-.568-.993-1.332-1.356-2.01a18 18 0 0 1-.401-.8");
}

.vbk4lwwtg {
  stop-color: var(--svg-color--6e4546, #6E4546);
}

.vjn09nwef {
  d: path("m20.257 19.66l-.097.063l-.045.172c-.173.61-.45 1.178-.723 1.521a.9.9 0 0 1-1.482-1.014l-.028-.003c.507-.018 1.666-.296 2.301-.698z");
}

.vk-6y3skm {
  stop-color: var(--svg-color--3067d9, #3067D9);
}

.vz0gmorja {
  stop-color: var(--svg-color--43c7f4, #43C7F4);
}

.w1j5cub_o {
  d: path("M25.376 16.67c.481.65.875 1.256 1.147 1.847c-.438.71-.838 1.593-1.031 2.506c-.325 1.532-.106 3.23 1.409 4.82a1 1 0 0 1-1.448 1.38c-2.035-2.135-2.358-4.535-1.918-6.614c.33-1.56 1.085-2.937 1.841-3.938");
}

.watehllxo {
  stop-color: var(--svg-color--0d8cba, #0D8CBA);
}

.wdnp9-ozl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.842 19.483c-.446.085-1.31.05-1.718-.8c-.515-1.073.889-2.263 2.059-1.136");
}

.wibulobyi {
  fill-rule: evenodd;
  d: path("M10.885 22.864a1 1 0 0 1 1.296.566c.432 1.105 1.206 3.882-.793 6.367a1 1 0 0 1-1.558-1.254c1.3-1.616.847-3.467.488-4.383a1 1 0 0 1 .567-1.296");
}

.wpwnbokgv {
  fill: var(--svg-color--2bbafe, #2BBAFE);
  d: path("M25.376 16.67c.481.65.875 1.256 1.147 1.847c-.438.71-.838 1.593-1.031 2.506c-.325 1.532-.106 3.23 1.409 4.82a1 1 0 0 1-1.448 1.38c-2.035-2.135-2.358-4.535-1.918-6.614c.33-1.56 1.085-2.937 1.841-3.938");
}

.wsgdl5_-l {
  stop-color: var(--svg-color--f3c893, #F3C893);
  stop-opacity: 0;
}

.wyvizzypi {
  stop-color: var(--svg-color--4bdaff, #4BDAFF);
  stop-opacity: 0;
}

.x3o31dnkz {
  stop-color: var(--svg-color--f3c893, #F3C893);
}

.xipw8g_9r {
  stop-color: var(--svg-color--eb9530, #EB9530);
}

.xnhz5xbwr {
  stop-color: var(--svg-color--d6be6f, #D6BE6F);
  stop-opacity: 0;
}

.yl-cus5ut {
  stop-color: var(--svg-color--d6be6f, #D6BE6F);
}

.ytexaxy1f {
  stop-color: var(--svg-color--255eb1, #255EB1);
}

.z1h6bqbtn {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 2.519px;
  ry: 6.408px;
}

.z2yf7b4br {
  stop-color: var(--svg-color--3258a2, #3258A2);
}

.z4e-h3vsi {
  stop-color: var(--svg-color--b46518, #B46518);
}

.zb0grjbzu {
  stop-color: var(--svg-color--0d8cba, #0D8CBA);
  stop-opacity: 0;
}

.zc3_q-b7f {
  stop-color: var(--svg-color--ffe76d, #FFE76D);
}

.zmc0w_b6y {
  cx: 11.96px;
  cy: 20.938px;
  r: 0.816px;
}

.zt1awvtgj {
  d: path("m7.898 15.068l.008-.008a16 16 0 0 1 1.563-1.372c.145.34.35.781.594 1.236c.336.628.71 1.218 1.063 1.6c.223.242.418.275 1.034.269l.08-.001c.584-.008 1.573-.02 2.404.827c.842.828.814 1.78.797 2.362q-.004.112-.004.204v2.138a.5.5 0 0 0 .149.356l.631.622a1 1 0 0 1-1.404 1.425c-.69-.613-1.39-1.374-1.37-2.597l-.006-1.944c0-.094.002-.186.003-.266v-.008c.001-.086.003-.159.002-.229c0-.14-.006-.234-.019-.309a.53.53 0 0 0-.184-.33l-.01-.01l-.01-.01c-.204-.211-.382-.237-1.04-.23h-.028c-.618.006-1.64.016-2.496-.915c-.524-.568-.993-1.332-1.356-2.01a18 18 0 0 1-.401-.8");
}

</style>
