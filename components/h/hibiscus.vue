<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ii4EPle)" class="sfcni_b2g"/><path fill="url(#iWqgyEe)" class="sfcni_b2g"/><path class="i3191zady"/><path fill="url(#iJmxsld)" class="l8142ysoh"/><path fill="url(#igoHKbd)" class="l8142ysoh"/><path fill="url(#i5VNmhe)" class="uyolz6_vh"/><path fill="url(#i5M7HXb)" class="uyolz6_vh"/><g filter="url(#i3osHob)"><path fill="url(#iFFY23d)" class="o4avel9sm"/></g><g filter="url(#iz9jhze)"><path fill="url(#iF48h5x)" class="njf4txb6q"/></g><g filter="url(#i0QDFnc)"><path class="udk5s6g1e"/></g><path class="t9dihij5s"/><g filter="url(#i3x4lUw)"><path fill="url(#ifYQErd)" class="wf-b1wuyi"/></g><g filter="url(#iu3kMfe)"><path fill="url(#iLeF7Md)" class="t3ew_2b5p"/></g><g filter="url(#iM1Radd)"><path fill="url(#iWpMG0c)" class="dsmtm8b-b"/></g><g filter="url(#iRmYF3a)"><path class="bjgl3vb_n"/></g><path fill="url(#iRPRSId)" class="krcb2opnz"/><path fill="url(#idUPkJc)" class="krcb2opnz"/><path fill="url(#irR6AVc)" class="y790zibhg"/><circle fill="url(#igRlqoI)" class="mg_zdo3zn"/><circle fill="url(#iHyGlnB)" class="z3-1f6ehe"/><circle fill="url(#iYgMCbe)" class="gf18g4a9h"/><circle fill="url(#iMNunTb)" class="ql4j3cwrv"/><circle fill="url(#iDwpK3c)" class="jbr19xgjv"/><g filter="url(#i5NdSbe)"><path fill="url(#iwY1Ljc)" class="m7d1t9b6d"/></g><g filter="url(#iMU9Thd)"><path stroke="url(#ipQk7nc)" class="a0y9-zbyr"/></g><g filter="url(#iueMsQd)"><path stroke="url(#iPzAZHb)" class="rf7v0oedk"/></g><g filter="url(#iABudpd)"><path stroke="url(#iv0rSsd)" class="kd-jbxbvx"/></g><g filter="url(#iipGctc)"><path stroke="url(#iDzibec)" class="i1pwqtdpn"/></g><g filter="url(#iEFbdpd)"><path stroke="url(#ibJVC5d)" class="vhf9g6boa"/></g><g filter="url(#i9milXb)"><path stroke="url(#iiqsRlc)" class="m200-6bsz"/></g><g filter="url(#ix01OMe)"><path stroke="url(#i71q6eb)" class="kww15ds4u"/></g><g filter="url(#i7HPwzd)"><path stroke="url(#i73S6wd)" class="dqpx81bfz"/></g><g filter="url(#iSRw7Ge)"><path stroke="url(#iH3KLyM)" class="qt_i64b8l"/></g><g filter="url(#iSuC35c)"><path stroke="url(#i9qIGHs)" class="ta9orvnvy"/></g><defs><filter id="i3osHob" width="24.858" height="24.159" x="2.114" y="2.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".25"/></filter><filter id="iz9jhze" width="9.778" height="10.421" x="14.422" y="15.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".25"/></filter><filter id="i0QDFnc" width="16.626" height="16.269" x="5.595" y="6.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".5"/></filter><filter id="i3x4lUw" width="14.194" height="13.859" x="7.445" y="7.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".125"/></filter><filter id="iu3kMfe" width="7.094" height="7.547" x="7.422" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".25"/></filter><filter id="iM1Radd" width="6.345" height="6.683" x="14.453" y="15.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".125"/></filter><filter id="iRmYF3a" width="5.234" height="5.234" x="11.758" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".25"/></filter><filter id="i5NdSbe" width="3.068" height="5.169" x="17.978" y="16.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="iMU9Thd" width="4.606" height="3.44" x="13.697" y="7.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="iueMsQd" width="3.153" height="5.822" x="18.988" y="10.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".15"/></filter><filter id="iABudpd" width="7.325" height="3.18" x="2.728" y="8.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="iipGctc" width="6.169" height="6.356" x="13.541" y="1.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="iEFbdpd" width="4.568" height="8.387" x="22.916" y="7.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="i9milXb" width="4.459" height="8.762" x="19.884" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="ix01OMe" width="4.888" height="3.262" x="10.353" y="23.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="i7HPwzd" width="2.881" height="3.225" x="11.997" y="11.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".1"/></filter><filter id="iSRw7Ge" width="3.491" height="6.633" x="23.877" y="22.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".2"/></filter><filter id="iSuC35c" width="3.631" height="2.131" x="26.067" y="16.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7361" stdDeviation=".1"/></filter><radialGradient id="iWqgyEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93396 3.54566 -5.74212 -3.132 25.099 22.876)" gradientUnits="userSpaceOnUse"><stop class="jferhgbol"/><stop offset="1" class="xrprg4bzi"/></radialGradient><radialGradient id="iJmxsld" cx="0" cy="0" r="1" gradientTransform="matrix(.68261 5.40625 -7.85268 .9915 24.958 16.781)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="zdmmymboo"/><stop offset="1" class="o9er3-qbj"/></radialGradient><radialGradient id="igoHKbd" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 2.21875 -3.22277 3.54051 22.89 18.406)" gradientUnits="userSpaceOnUse"><stop class="o9er3-qbj"/><stop offset="1" class="zdmmymboo"/></radialGradient><radialGradient id="i5M7HXb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 .593 -2.2815 6.97328 8.828 4.403)" gradientUnits="userSpaceOnUse"><stop class="pdnagqb8i"/><stop offset="1" class="i_71-zb8u"/></radialGradient><radialGradient id="iFFY23d" cx="0" cy="0" r="1" gradientTransform="matrix(10.48595 -13.43967 34.09847 26.60444 7.905 25.565)" gradientUnits="userSpaceOnUse"><stop class="sf7gw4ejm"/><stop offset="1" class="hj6hpjrip"/></radialGradient><radialGradient id="ifYQErd" cx="0" cy="0" r="1" gradientTransform="matrix(6.875 -9.625 18.81286 13.43777 12.453 17.938)" gradientUnits="userSpaceOnUse"><stop class="ssevqkbec"/><stop offset="1" class="pb8bqj97b"/></radialGradient><radialGradient id="iRPRSId" cx="0" cy="0" r="1" gradientTransform="rotate(151.213 6.026 9)scale(1.62237 1.59316)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="idUPkJc" cx="0" cy="0" r="1" gradientTransform="rotate(-119.985 11.037 2.942)scale(1.61237 1.06537)" gradientUnits="userSpaceOnUse"><stop class="kv5-628si"/><stop offset="1" class="fwx8u-ghb"/></radialGradient><radialGradient id="igRlqoI" cx="0" cy="0" r="1" gradientTransform="matrix(-.41362 .22727 -.22318 -.40617 10.415 9.393)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="iHyGlnB" cx="0" cy="0" r="1" gradientTransform="matrix(-.41362 .22727 -.22318 -.40617 11.637 9.437)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="iYgMCbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.41362 .22727 -.22318 -.40617 12.23 10.528)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="iMNunTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.41362 .22727 -.22318 -.40617 11.262 11.296)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="iDwpK3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.41362 .22727 -.22318 -.40617 10.315 10.61)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="lug7bnblh"/></radialGradient><radialGradient id="iPzAZHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 .92188 -2.0092 -2.92865 21.531 11.703)" gradientUnits="userSpaceOnUse"><stop class="byg1lfhaw"/><stop offset="1" class="z1_bmtabk"/></radialGradient><radialGradient id="iDzibec" cx="0" cy="0" r="1" gradientTransform="rotate(97.306 7.44 9.457)scale(2.45745 14.2482)" gradientUnits="userSpaceOnUse"><stop class="wf1cw3thj"/><stop offset="0" class="wf1cw3thj"/><stop offset="1" class="h7jl1db2b"/></radialGradient><radialGradient id="ibJVC5d" cx="0" cy="0" r="1" gradientTransform="rotate(93.551 8.611 16.732)scale(3.24125 9.20957)" gradientUnits="userSpaceOnUse"><stop class="wf1cw3thj"/><stop offset="0" class="wf1cw3thj"/><stop offset="1" class="h7jl1db2b"/></radialGradient><linearGradient id="ii4EPle" x1="24.024" x2="21.868" y1="28.517" y2="22.662" gradientUnits="userSpaceOnUse"><stop class="x_-5_dy8m"/><stop offset=".931" class="p2yjnnawe"/></linearGradient><linearGradient id="i5VNmhe" x1="4.833" x2="39.364" y1="22.847" y2="-.131" gradientUnits="userSpaceOnUse"><stop class="o5kqig7us"/><stop offset="1" class="stzg02bpr"/></linearGradient><linearGradient id="iF48h5x" x1="15.234" x2="21.141" y1="22.719" y2="22.719" gradientUnits="userSpaceOnUse"><stop class="mozfejb2q"/><stop offset="1" class="ff5a3qb1a"/></linearGradient><linearGradient id="iLeF7Md" x1="12.234" x2="9.734" y1="15.781" y2="10.156" gradientUnits="userSpaceOnUse"><stop class="ho0qp5bzw"/><stop offset="1" class="npv7bccvy"/></linearGradient><linearGradient id="iWpMG0c" x1="14.703" x2="19.297" y1="19" y2="18.685" gradientUnits="userSpaceOnUse"><stop class="qk5cf76mj"/><stop offset="1" class="s_g22k_1c"/></linearGradient><linearGradient id="irR6AVc" x1="11.047" x2="15.004" y1="10.5" y2="15.075" gradientUnits="userSpaceOnUse"><stop class="xj1ts9b8a"/><stop offset="1" class="o-ywv3d2n"/></linearGradient><linearGradient id="iwY1Ljc" x1="20.891" x2="18.125" y1="17.625" y2="22.797" gradientUnits="userSpaceOnUse"><stop class="byg1lfhaw"/><stop offset="1" class="z1_bmtabk"/></linearGradient><linearGradient id="ipQk7nc" x1="18.188" x2="15.941" y1="9.234" y2="10.59" gradientUnits="userSpaceOnUse"><stop class="byg1lfhaw"/><stop offset="1" class="z1_bmtabk"/></linearGradient><linearGradient id="iv0rSsd" x1="9.766" x2="2.828" y1="9.187" y2="11.187" gradientUnits="userSpaceOnUse"><stop class="wf1cw3thj"/><stop offset="1" class="h7jl1db2b"/></linearGradient><linearGradient id="iiqsRlc" x1="25.078" x2="20.377" y1="17.188" y2="16.941" gradientUnits="userSpaceOnUse"><stop class="wf1cw3thj"/><stop offset="1" class="h7jl1db2b"/></linearGradient><linearGradient id="i71q6eb" x1="14.829" x2="10.427" y1="24.47" y2="25.203" gradientUnits="userSpaceOnUse"><stop class="tybv6xbjn"/><stop offset="1" class="h7jl1db2b"/></linearGradient><linearGradient id="i73S6wd" x1="14.953" x2="14.942" y1="14.469" y2="11.834" gradientUnits="userSpaceOnUse"><stop class="khyigubcr"/><stop offset="1" class="gk4t0zbyy"/></linearGradient><linearGradient id="iH3KLyM" x1="27.21" x2="27.163" y1="28.571" y2="23.017" gradientUnits="userSpaceOnUse"><stop class="ks5jkebvy"/><stop offset="1" class="r9a5zcqko"/></linearGradient><linearGradient id="i9qIGHs" x1="29.897" x2="29.894" y1="18.156" y2="16.619" gradientUnits="userSpaceOnUse"><stop class="ks5jkebvy"/><stop offset="1" class="r758j4bxm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hibiscus" /></template>
<style>
.a0y9-zbyr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.703 9.938c-.156-.792-1.312-2.344-3.406-2.235");
}

.bjgl3vb_n {
  fill: var(--svg-color--e52a8a, #E52A8A);
  d: path("M14.375 16.804a2.117 2.117 0 1 0 0-4.234a2.117 2.117 0 0 0 0 4.234");
}

.byg1lfhaw {
  stop-color: var(--svg-color--ff78bc, #FF78BC);
}

.dqpx81bfz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m12.297 11.844l2.281 2.625");
}

.dsmtm8b-b {
  d: path("M14.703 15.594v5.437c.698.563 2.55 1.35 4.375 0s1.573-4.187 1.219-5.437z");
}

.ff5a3qb1a {
  stop-color: var(--svg-color--f058c6, #F058C6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwx8u-ghb {
  stop-color: var(--svg-color--f5c72a, #F5C72A);
  stop-opacity: 0;
}

.gf18g4a9h {
  cx: 11.911px;
  cy: 10.685px;
  r: 0.567px;
}

.gk4t0zbyy {
  stop-color: var(--svg-color--ffee64, #FFEE64);
  stop-opacity: 0;
}

.h7jl1db2b {
  stop-color: var(--svg-color--ff88d5, #FF88D5);
  stop-opacity: 0;
}

.hj6hpjrip {
  stop-color: var(--svg-color--ff67d9, #FF67D9);
}

.ho0qp5bzw {
  stop-color: var(--svg-color--e73790, #E73790);
}

.i_71-zb8u {
  stop-color: var(--svg-color--ff9bd8, #FF9BD8);
  stop-opacity: 0;
}

.i1pwqtdpn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.14 2.563c1.626-.021 4.894.98 4.97 5.156");
}

.i3191zady {
  fill: var(--svg-color--589550, #589550);
  d: path("M24.425 22.615h-4.233v-7.78a7.52 7.52 0 0 1 4.7.66l4.59 2.33c.23.12.31.4.18.63a9.1 9.1 0 0 1-5.238 4.16");
}

.jbr19xgjv {
  cx: 9.995px;
  cy: 10.768px;
  r: 0.567px;
}

.jferhgbol {
  stop-color: var(--svg-color--5c9452, #5C9452);
}

.kd-jbxbvx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.328 10.625C4.1 9.542 6.403 7.737 9.453 9.187");
}

.khyigubcr {
  stop-color: var(--svg-color--ffee64, #FFEE64);
}

.krcb2opnz {
  d: path("M14.542 16.475a1.95 1.95 0 1 0 0-3.9a1.95 1.95 0 0 0 0 3.9");
}

.ks5jkebvy {
  stop-color: var(--svg-color--7daf70, #7DAF70);
}

.kv5-628si {
  stop-color: var(--svg-color--f5c72a, #F5C72A);
}

.kww15ds4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.953 25.969c.802-.01 2.663-.438 3.688-2.063");
}

.l8142ysoh {
  d: path("M24.425 22.615h-4.233v-7.78a7.52 7.52 0 0 1 4.7.66l4.59 2.33c.23.12.31.4.18.63a9.1 9.1 0 0 1-5.238 4.16");
}

.lug7bnblh {
  stop-color: var(--svg-color--ffc94c, #FFC94C);
}

.m200-6bsz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M22.422 17.875c.562.604 1.531 1.831 1.281 4.031s-2.281 3.24-3.219 3.532");
}

.m7d1t9b6d {
  d: path("M20.572 16.936a.2.2 0 1 0-.394.066zm-2.083 3.823a.2.2 0 1 0 .179.357zm1.689-3.757c.163.97.185 2.82-1.69 3.757l.18.357c2.125-1.062 2.074-3.17 1.904-4.18z");
}

.mg_zdo3zn {
  cx: 10.096px;
  cy: 9.551px;
  r: 0.567px;
}

.mozfejb2q {
  stop-color: var(--svg-color--f058c6, #F058C6);
}

.njf4txb6q {
  d: path("M14.922 20.219v4.093c4.5 4.094 9.187-.687 8.75-4.093c-.35-2.725-2.48-3.636-3.5-3.75z");
}

.npv7bccvy {
  stop-color: var(--svg-color--ed3fa3, #ED3FA3);
  stop-opacity: 0;
}

.o-ywv3d2n {
  stop-color: var(--svg-color--ffe646, #FFE646);
}

.o4avel9sm {
  d: path("M23.797 8.59a5.01 5.01 0 0 0-4.485-.13c.14-1.498-.37-3.042-1.553-4.151a5.064 5.064 0 0 0-7.147.23a5.03 5.03 0 0 0-1.294 4.18A5.05 5.05 0 0 0 5 9.199a5.06 5.06 0 0 0-1.627 6.963c.749 1.211 2.444 1.76 3.729 2.037c-.657 1.073-1.427 2.623-1.131 3.945a5.043 5.043 0 0 0 6.028 3.837a4.96 4.96 0 0 0 2.95-1.914a5.08 5.08 0 0 0 3.134 1.692a5.066 5.066 0 0 0 5.686-4.336a5 5 0 0 0-.87-3.56a5.044 5.044 0 0 0 .898-9.274");
}

.o5kqig7us {
  stop-color: var(--svg-color--fe65d5, #FE65D5);
}

.o9er3-qbj {
  stop-color: var(--svg-color--4d844d, #4D844D);
}

.p2yjnnawe {
  stop-color: var(--svg-color--567343, #567343);
}

.pb8bqj97b {
  stop-color: var(--svg-color--ed4aa5, #ED4AA5);
  stop-opacity: 0;
}

.pdnagqb8i {
  stop-color: var(--svg-color--ff9bd8, #FF9BD8);
}

.qk5cf76mj {
  stop-color: var(--svg-color--e32d95, #E32D95);
}

.ql4j3cwrv {
  cx: 10.942px;
  cy: 11.453px;
  r: 0.567px;
}

.qt_i64b8l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M24.427 23.038c.761.805 2.305 3.04 2.39 5.533");
}

.r758j4bxm {
  stop-color: var(--svg-color--8fbf69, #8FBF69);
  stop-opacity: 0;
}

.r9a5zcqko {
  stop-color: var(--svg-color--8fbf69, #8FBF69);
}

.rf7v0oedk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.438 10.469c1.109.328 3.043 1.772 1.906 4.922");
}

.s_g22k_1c {
  stop-color: var(--svg-color--e32d95, #E32D95);
  stop-opacity: 0;
}

.sf7gw4ejm {
  stop-color: var(--svg-color--ff83e8, #FF83E8);
}

.sfcni_b2g {
  d: path("M24.892 15.495c-3.7-1.85-8.39-.31-10.33 3.51l-.35.68a.5.5 0 0 0 .023.502a.5.5 0 0 0-.223.418v.76c0 4.28 3.48 7.78 7.61 7.81l5.15.01c.26 0 .46-.22.45-.48a9.1 9.1 0 0 0-2.798-6.09a9.1 9.1 0 0 0 5.238-4.16a.45.45 0 0 0-.18-.63z");
}

.ssevqkbec {
  stop-color: var(--svg-color--ed49a5, #ED49A5);
}

.stzg02bpr {
  stop-color: var(--svg-color--ff7cd0, #FF7CD0);
}

.t3ew_2b5p {
  d: path("m14.016 14.688l-4.953 2.015c-.542-.427-1.141-1.719-1.141-3.375c0-1.997 1.719-2.974 2.656-3.172z");
}

.t9dihij5s {
  fill: var(--svg-color--ea2195, #EA2195);
  d: path("M18.423 9.728a.27.27 0 0 1-.228-.159a4.079 4.079 0 0 0-7.486.089a.27.27 0 0 1-.22.163A4.079 4.079 0 0 0 8.32 17a.27.27 0 0 1 .09.26q-.077.39-.078.803a4.078 4.078 0 0 0 6.252 3.451a.27.27 0 0 1 .277-.006a4.078 4.078 0 0 0 5.979-4.463a.27.27 0 0 1 .079-.258a4.078 4.078 0 0 0-2.494-7.058");
}

.ta9orvnvy {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.367 16.625l3.031 1.531");
}

.tybv6xbjn {
  stop-color: var(--svg-color--ff8fd8, #FF8FD8);
}

.udk5s6g1e {
  fill: var(--svg-color--f03ebd, #F03EBD);
  d: path("M17.613 10.321a.27.27 0 0 1-.229-.159a3.884 3.884 0 0 0-7.122.084a.27.27 0 0 1-.22.164a3.884 3.884 0 0 0-2.065 6.83c.075.063.11.163.09.26a3.883 3.883 0 0 0 5.873 4.048a.27.27 0 0 1 .278-.007a3.884 3.884 0 0 0 5.688-4.247a.27.27 0 0 1 .08-.258a3.884 3.884 0 0 0-2.373-6.715");
}

.uyolz6_vh {
  d: path("M24.552 8.129a5.43 5.43 0 0 0-4.85-.14c.15-1.618-.4-3.286-1.68-4.484a5.48 5.48 0 0 0-7.73.25c-1.18 1.258-1.63 2.926-1.4 4.514a5.463 5.463 0 0 0-6.43 8.04a5.42 5.42 0 0 0 3.48 2.447a5.4 5.4 0 0 0-.67 4.015a5.454 5.454 0 0 0 6.52 4.145a5.37 5.37 0 0 0 3.19-2.068a5.5 5.5 0 0 0 3.39 1.828c2.99.4 5.74-1.698 6.15-4.684a5.4 5.4 0 0 0-.94-3.846a5.45 5.45 0 0 0 3.22-2.646c1.42-2.647.41-5.953-2.25-7.371");
}

.vhf9g6boa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M23.516 8.219c1.49.427 4.437 3.156 2.968 7.187");
}

.wf-b1wuyi {
  d: path("M18.02 10.263a.27.27 0 0 1-.228-.16a3.637 3.637 0 0 0-6.66.08a.27.27 0 0 1-.22.164a3.636 3.636 0 0 0-1.932 6.386c.075.064.11.163.092.26q-.068.34-.068.7a3.636 3.636 0 0 0 5.56 3.085a.27.27 0 0 1 .277-.006a3.636 3.636 0 0 0 5.318-3.971a.27.27 0 0 1 .08-.259a3.636 3.636 0 0 0-2.219-6.28");
}

.wf1cw3thj {
  stop-color: var(--svg-color--ffa8e0, #FFA8E0);
}

.wwzg2xbtb {
  stop-color: var(--svg-color--ffef81, #FFEF81);
}

.x_-5_dy8m {
  stop-color: var(--svg-color--76a04a, #76A04A);
}

.xj1ts9b8a {
  stop-color: var(--svg-color--ffb236, #FFB236);
}

.xrprg4bzi {
  stop-color: var(--svg-color--5c9452, #5C9452);
  stop-opacity: 0;
}

.y790zibhg {
  d: path("M14.492 15.075c-.14 0-.28-.06-.38-.17l-3.78-4.33a.505.505 0 0 1 .05-.71c.21-.18.52-.16.71.05l3.79 4.33c.18.21.16.52-.05.71a.6.6 0 0 1-.34.12");
}

.z1_bmtabk {
  stop-color: var(--svg-color--ff78bc, #FF78BC);
  stop-opacity: 0;
}

.z3-1f6ehe {
  cx: 11.317px;
  cy: 9.594px;
  r: 0.567px;
}

.zdmmymboo {
  stop-color: var(--svg-color--4d844d, #4D844D);
  stop-opacity: 0;
}

</style>
