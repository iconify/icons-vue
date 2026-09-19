<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ir8smLe)" class="fbpp-baoo"/><rect fill="url(#iFZFAHd)" class="vlj1hwbxm"/><rect fill="url(#iVVkd1c)" class="vlj1hwbxm"/><rect fill="url(#i1gDxyb)" class="vlj1hwbxm"/><rect fill="url(#itUTe3c)" class="vlj1hwbxm"/><g filter="url(#iHYFNBb)"><path fill="url(#ig1mZec)" class="g5-u1hwtp"/><path fill="url(#ioDOu1d)" class="g5-u1hwtp"/></g><circle fill="url(#iuNAZMb)" class="sb-8ey0_f"/><g filter="url(#i8KjDrc)"><path class="z0-mjyb8a"/></g><g filter="url(#ibhld5d)"><path stroke="url(#it586iq)" class="a293aygfy"/></g><g filter="url(#iNa1gOe)"><rect transform="rotate(-8.905 12.43 25.123)" class="st7sxbbqs"/></g><g filter="url(#iDPp5Md)"><rect transform="rotate(-8.905 12.43 27.494)" class="e60ie6bjj"/></g><rect fill="url(#iRZg9uD)" transform="rotate(-8.905 11.685 27.463)" class="vnl4dzbbf"/><rect fill="url(#iMKH0dc)" transform="rotate(-8.905 11.685 27.463)" class="vnl4dzbbf"/><rect fill="url(#iQw9b8c)" transform="rotate(-8.905 11.685 27.463)" class="vnl4dzbbf"/><rect fill="url(#iNhme0c)" transform="rotate(-8.905 11.685 27.463)" class="vnl4dzbbf"/><rect fill="url(#igJoQRa)" transform="rotate(-8.905 11.685 25.086)" class="tt7n4xbfq"/><rect fill="url(#iQNjDSr)" transform="rotate(-8.905 11.685 25.086)" class="tt7n4xbfq"/><rect fill="url(#ivQixjp)" transform="rotate(-8.905 11.685 25.086)" class="tt7n4xbfq"/><rect fill="url(#iA8ECmu)" transform="rotate(-8.905 11.685 25.086)" class="tt7n4xbfq"/><defs><linearGradient id="iFZFAHd" x1="19.297" x2="12.516" y1="25.802" y2="25.802" gradientUnits="userSpaceOnUse"><stop class="yhc2qb2fj"/><stop offset="1" class="qc1tvvbwv"/></linearGradient><linearGradient id="iVVkd1c" x1="12.181" x2="13.837" y1="26.313" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="j6z8080tb"/><stop offset="1" class="pv24bwb_g"/></linearGradient><linearGradient id="itUTe3c" x1="17.462" x2="17.462" y1="28.891" y2="27.625" gradientUnits="userSpaceOnUse"><stop class="vixantbyu"/><stop offset="1" class="cl06h3bhp"/></linearGradient><linearGradient id="iuNAZMb" x1="16.298" x2="19.72" y1="8.027" y2="5.361" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset=".594" class="vc--wpv5i"/></linearGradient><linearGradient id="it586iq" x1="19.72" x2="15.714" y1="10.997" y2="20.54" gradientUnits="userSpaceOnUse"><stop class="mi8-19d0m"/><stop offset="1" class="f3ls4qbhy"/></linearGradient><linearGradient id="iRZg9uD" x1="15.744" x2="15.823" y1="27.472" y2="28.687" gradientUnits="userSpaceOnUse"><stop class="wyy8u7b-s"/><stop offset="1" class="xhlnhyb9q"/></linearGradient><linearGradient id="iMKH0dc" x1="16.715" x2="16.713" y1="28.542" y2="27.751" gradientUnits="userSpaceOnUse"><stop class="a3vjwegav"/><stop offset="1" class="h9jyxxfzz"/></linearGradient><linearGradient id="iQw9b8c" x1="11.587" x2="14.374" y1="28.086" y2="27.938" gradientUnits="userSpaceOnUse"><stop class="oo9dllbbc"/><stop offset="1" class="i6yqonbbm"/></linearGradient><linearGradient id="igJoQRa" x1="15.744" x2="15.823" y1="25.096" y2="26.31" gradientUnits="userSpaceOnUse"><stop class="wyy8u7b-s"/><stop offset="1" class="xhlnhyb9q"/></linearGradient><linearGradient id="iQNjDSr" x1="16.715" x2="16.713" y1="26.165" y2="25.374" gradientUnits="userSpaceOnUse"><stop class="a3vjwegav"/><stop offset="1" class="h9jyxxfzz"/></linearGradient><linearGradient id="ivQixjp" x1="11.587" x2="14.374" y1="25.71" y2="25.561" gradientUnits="userSpaceOnUse"><stop class="oo9dllbbc"/><stop offset="1" class="i6yqonbbm"/></linearGradient><radialGradient id="ir8smLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .9375 -2.17141 -.25333 16.337 29.11)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="zrmoyywvt"/><stop offset="1" class="z2v04zqaz"/></radialGradient><radialGradient id="i1gDxyb" cx="0" cy="0" r="1" gradientTransform="matrix(.01964 .82464 -3.67138 .08742 17.305 22.64)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="ku6nqt5lb"/><stop offset="1" class="ittqzo2wu"/></radialGradient><radialGradient id="ig1mZec" cx="0" cy="0" r="1" gradientTransform="rotate(138.066 8.221 7.81)scale(9.91369 8.17473)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="mtq2fbenc"/><stop offset="1" class="hy-2zjs3g"/></radialGradient><radialGradient id="ioDOu1d" cx="0" cy="0" r="1" gradientTransform="matrix(-12.31245 -7.81251 7.51457 -11.8429 20.493 13.438)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="i0jrfjt-e"/><stop offset="1" class="swub81brh"/></radialGradient><radialGradient id="iNhme0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.0047 .8375 -4.95703 -.0278 18.58 27.84)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="smsad79_a"/><stop offset="1" class="r3quaccrd"/></radialGradient><radialGradient id="iA8ECmu" cx="0" cy="0" r="1" gradientTransform="matrix(-.0047 .8375 -4.95701 -.02777 18.58 25.463)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="smsad79_a"/><stop offset="1" class="r3quaccrd"/></radialGradient><filter id="iHYFNBb" width="17.547" height="21.126" x="7.258" y="1.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.666667 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20513"/></filter><filter id="i8KjDrc" width="8.219" height="12.935" x="11.884" y="10.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.572549 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20513"/></filter><filter id="ibhld5d" width="7.719" height="12.964" x="12.141" y="10.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20513" stdDeviation=".125"/></filter><filter id="iNa1gOe" width="7.242" height="2.459" x="12.256" y="23.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20513" stdDeviation=".125"/></filter><filter id="iDPp5Md" width="7.242" height="2.459" x="12.256" y="26.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20513" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:light-bulb" /></template>
<style>
.a293aygfy {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.879 22.739c0-4.771.731-5.533 1.515-6.324a3.484 3.484 0 1 0-4.788 0c.784.791 1.511 2.161 1.511 6.324");
}

.a3vjwegav {
  stop-color: var(--svg-color--8a68a9, #8A68A9);
}

.cl06h3bhp {
  stop-color: var(--svg-color--7e5f9e, #7E5F9E);
  stop-opacity: 0;
}

.e60ie6bjj {
  width: 6.811px;
  height: 1.07px;
  x: 12.43px;
  y: 27.494px;
  fill: var(--svg-color--7e6693, #7E6693);
  rx: 0.535px;
}

.f3ls4qbhy {
  stop-color: var(--svg-color--ffbf5c, #FFBF5C);
  stop-opacity: 0;
}

.fbpp-baoo {
  cx: 15.868px;
  cy: 28.102px;
  r: 1.773px;
}

.ft5dv1b6b {
  fill: none;
}

.g5-u1hwtp {
  d: path("M15.767 22.969h.054c.556-.003 1.834-.024 2.347-.117c.55-.1.621-.375.719-.805c.602-2.654 1.612-3.674 2.288-4.356q.157-.157.286-.296c.293-.322.547-.606.74-.825a8.648 8.648 0 1 0-12.644-.057c.2.226.472.531.792.882a7 7 0 0 0 .286.296c.675.682 1.686 1.703 2.288 4.356c.098.43.169.705.719.805c.511.093 1.546.114 2.07.116z");
}

.h9jyxxfzz {
  stop-color: var(--svg-color--dec2e3, #DEC2E3);
  stop-opacity: 0;
}

.hy-2zjs3g {
  stop-color: var(--svg-color--ffcd4b, #FFCD4B);
}

.i0jrfjt-e {
  stop-color: var(--svg-color--ffb239, #FFB239);
  stop-opacity: 0;
}

.i6yqonbbm {
  stop-color: var(--svg-color--958387, #958387);
  stop-opacity: 0;
}

.ittqzo2wu {
  stop-color: var(--svg-color--c8bccb, #C8BCCB);
  stop-opacity: 0;
}

.j6z8080tb {
  stop-color: var(--svg-color--8a7b88, #8A7B88);
}

.ku6nqt5lb {
  stop-color: var(--svg-color--ede2eb, #EDE2EB);
}

.mi8-19d0m {
  stop-color: var(--svg-color--ffbf5c, #FFBF5C);
}

.mtq2fbenc {
  stop-color: var(--svg-color--ffec87, #FFEC87);
}

.oo9dllbbc {
  stop-color: var(--svg-color--958387, #958387);
}

.pv24bwb_g {
  stop-color: var(--svg-color--8a7b88, #8A7B88);
  stop-opacity: 0;
}

.qc1tvvbwv {
  stop-color: var(--svg-color--947c8d, #947C8D);
}

.r3quaccrd {
  stop-color: var(--svg-color--e5c9e3, #E5C9E3);
  stop-opacity: 0;
}

.sb-8ey0_f {
  cx: 17.462px;
  cy: 6.953px;
  r: 3.328px;
}

.smsad79_a {
  stop-color: var(--svg-color--fcf0fc, #FCF0FC);
}

.st7sxbbqs {
  width: 6.811px;
  height: 1.07px;
  x: 12.43px;
  y: 25.123px;
  fill: var(--svg-color--7e6693, #7E6693);
  rx: 0.535px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swub81brh {
  stop-color: var(--svg-color--ffb239, #FFB239);
}

.tt7n4xbfq {
  width: 8.32px;
  height: 1.102px;
  x: 11.685px;
  y: 25.086px;
  rx: 0.551px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vixantbyu {
  stop-color: var(--svg-color--7e5f9e, #7E5F9E);
}

.vlj1hwbxm {
  width: 6.781px;
  height: 6.719px;
  x: 12.516px;
  y: 22.172px;
  rx: 1.25px;
}

.vnl4dzbbf {
  width: 8.32px;
  height: 1.102px;
  x: 11.685px;
  y: 27.463px;
  rx: 0.551px;
}

.wyy8u7b-s {
  stop-color: var(--svg-color--b1969a, #B1969A);
}

.xhlnhyb9q {
  stop-color: var(--svg-color--dad2e2, #DAD2E2);
}

.yhc2qb2fj {
  stop-color: var(--svg-color--cdc2d1, #CDC2D1);
}

.z0-mjyb8a {
  fill: var(--svg-color--ffad55, #FFAD55);
  d: path("M15.479 22.966c-.035-2.172-.208-3.602-.472-4.598c-.303-1.147-.728-1.72-1.178-2.173l-.005-.006l-.006-.005a2.984 2.984 0 1 1 4.101 0l-.006.005l-.006.006c-.441.446-.872.98-1.179 2.118c-.266.985-.44 2.42-.475 4.651c.302-.005.663-.014 1.001-.03c.036-2.168.206-3.496.44-4.36c.252-.937.577-1.325.918-1.67a3.984 3.984 0 1 0-5.488 0c.333.337.662.758.917 1.72c.232.879.4 2.204.437 4.31c.347.02.712.028 1 .032");
}

.z2v04zqaz {
  stop-color: var(--svg-color--8e6aaa, #8E6AAA);
}

.zrmoyywvt {
  stop-color: var(--svg-color--ac90c6, #AC90C6);
}

</style>
