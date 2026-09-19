<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="c7owaubke"/><path fill="url(#i7tcahc)" class="ooyxpw46h"/><path fill="url(#ihZJH6c)" class="ooyxpw46h"/><path fill="url(#i9FPBQX)" class="ooyxpw46h"/><path fill="url(#igb71Rf)" class="ooyxpw46h"/><path fill="url(#ifJp3Pb)" class="ooyxpw46h"/><g filter="url(#iyPS9bb)"><path class="zo8ke71vh"/></g><g filter="url(#iSWR5yc)"><path class="ur5n04b0r"/><path fill="url(#ijJSPye)" class="lm0cklbhu"/></g><g filter="url(#iPxeZje)"><path class="ktwiu8bdi"/></g><g filter="url(#iKhnddd)"><path class="p9ifgsbfy"/></g><g filter="url(#iJ1YXGn)"><path class="xoe2znb0d"/></g><path class="g0c9a_bdy"/><path fill="url(#ize8G9b)" class="xepusvbbq"/><path fill="url(#i70SRDb)" class="xepusvbbq"/><path fill="url(#ifh8bTc)" class="xepusvbbq"/><path class="ghkwc7bmc"/><path fill="url(#iI2fhKY)" class="w-8axdw9p"/><path fill="url(#iJ46vhb)" class="w-8axdw9p"/><path fill="url(#inQ7DAb)" class="w-8axdw9p"/><g filter="url(#i6ije1b)"><path class="daslsfy7k"/></g><path fill="url(#ipKYlre)" class="d54yffbyd"/><path fill="url(#iTCqR8b)" class="d54yffbyd"/><path fill="url(#imyPQbb)" class="d54yffbyd"/><path fill="url(#iCSwnPd)" class="d54yffbyd"/><path fill="url(#iYonfGw)" class="d54yffbyd"/><g filter="url(#i137iww)"><rect fill="url(#iWcPKCe)" class="wvawutbhl"/></g><g filter="url(#iINV3be)"><rect class="keb3gdc6l"/></g><path fill="url(#itvVqrS)" class="lm0cklbhu"/><path fill="url(#iFaGAHd)" class="lm0cklbhu"/><g filter="url(#ipmxF9d)"><path stroke="url(#i3tAJ8d)" class="vzwx6yfqm"/></g><path fill="url(#i3r75Ne)" class="mzjby4bml"/><defs><radialGradient id="i7tcahc" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.316 1.809)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="mrg8g156k"/><stop offset="1" class="wbbh4mb5o"/></radialGradient><radialGradient id="ihZJH6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 20.126 11.569)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="towbt1bfr"/><stop offset="1" class="s8scx1bpu"/></radialGradient><radialGradient id="i9FPBQX" cx="0" cy="0" r="1" gradientTransform="rotate(148.855 8.296 8.616)scale(1.26883 10.2933)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="d0-at8b1l"/><stop offset=".652" class="kf5rkf18z"/></radialGradient><radialGradient id="igb71Rf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 19.197 14.8)" gradientUnits="userSpaceOnUse"><stop class="jb7vfybqr"/><stop offset="1" class="o43u81btt"/></radialGradient><radialGradient id="ifJp3Pb" cx="0" cy="0" r="1" gradientTransform="rotate(128.409 12.309 7.47)scale(3.53833 4.6463)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="ztpvcgb-y"/><stop offset="1" class="hhasrlbwz"/></radialGradient><radialGradient id="ijJSPye" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -2.78125 20.704 20.762)" gradientUnits="userSpaceOnUse"><stop class="mh9054bbp"/><stop offset="1" class="cv6x_l7vq"/></radialGradient><radialGradient id="i70SRDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.14698 -4.32661 0 8.614 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="p_us1bcmz"/><stop offset="1" class="w9896nonk"/></radialGradient><radialGradient id="ifh8bTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.874 12.698)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="vi1cnkhrt"/><stop offset="1" class="gzpoo_nab"/></radialGradient><radialGradient id="iI2fhKY" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.07411 -4.40172 0 13.174 9.562)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="p_us1bcmz"/><stop offset="1" class="w9896nonk"/></radialGradient><radialGradient id="inQ7DAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16274 -.82077 1.14253 -1.61856 15.598 15.877)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="i1xzen-dq"/><stop offset="1" class="icsq1bbfo"/></radialGradient><radialGradient id="ipKYlre" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45453 6.27643 -14.57501 -5.69986 23.473 14.936)" gradientUnits="userSpaceOnUse"><stop class="hhdj75n8v"/><stop offset="1" class="c87566b7j"/></radialGradient><radialGradient id="imyPQbb" cx="0" cy="0" r="1" gradientTransform="matrix(2.53066 1.77831 -3.77054 5.36574 14.657 14.612)" gradientUnits="userSpaceOnUse"><stop class="b-jo-_osr"/><stop offset="1" class="bmy67tbbi"/></radialGradient><radialGradient id="iCSwnPd" cx="0" cy="0" r="1" gradientTransform="matrix(9.51535 -2.34535 2.15924 8.76027 16.903 20.7)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="vptai38bv"/><stop offset="1" class="vqpc8gbud"/></radialGradient><radialGradient id="iYonfGw" cx="0" cy="0" r="1" gradientTransform="matrix(.90292 -.5788 .91809 1.43221 15.386 17.91)" gradientUnits="userSpaceOnUse"><stop class="ef9gcs5hx"/><stop offset="1" class="o463evbal"/></radialGradient><radialGradient id="itvVqrS" cx="0" cy="0" r="1" gradientTransform="rotate(-8.84 118.067 -28.762)scale(20.9074 21.9078)" gradientUnits="userSpaceOnUse"><stop offset=".934" class="lz22nac7d"/><stop offset="1" class="t-ej0lz2g"/></radialGradient><radialGradient id="iFaGAHd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.74995 4.50004 -8.23484 -21.50183 17.954 19.887)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="vjqngfski"/><stop offset="1" class="m4d8uf0de"/></radialGradient><radialGradient id="i3r75Ne" cx="0" cy="0" r="1" gradientTransform="matrix(3.09542 -1.98245 5.36717 8.38035 17.148 10.588)" gradientUnits="userSpaceOnUse"><stop class="rytyi-j4b"/><stop offset="1" class="fcvrbabtv"/></radialGradient><filter id="iyPS9bb" width="9.747" height="10.915" x="17.084" y="1.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation="1"/></filter><filter id="iSWR5yc" width="20.855" height="28.619" x="5.823" y="1.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.12549 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2204"/></filter><filter id="iPxeZje" width="14.735" height="10.475" x="11.706" y="13.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation="1"/></filter><filter id="iKhnddd" width="7.158" height="9.171" x="5.375" y="8.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation=".5"/></filter><filter id="iJ1YXGn" width="9.128" height="11.13" x="7.827" y="8.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation="1"/></filter><filter id="i6ije1b" width="11.711" height="22.797" x="15.73" y="1.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation="1"/></filter><filter id="i137iww" width="3.86" height="6.984" x="7.217" y="9.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation=".625"/></filter><filter id="iINV3be" width="5.193" height="8.957" x="11.629" y="7.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation=".875"/></filter><filter id="ipmxF9d" width="11.553" height="9.797" x="15.735" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2204" stdDeviation="1"/></filter><linearGradient id="ize8G9b" x1="5.823" x2="8.155" y1="13.355" y2="13.355" gradientUnits="userSpaceOnUse"><stop class="ny5ybgmod"/><stop offset="1" class="ipj2k3b_s"/></linearGradient><linearGradient id="iJ46vhb" x1="9.944" x2="12.707" y1="12.86" y2="12.86" gradientUnits="userSpaceOnUse"><stop class="e1qiqxrgs"/><stop offset="1" class="pcr0x3b6x"/></linearGradient><linearGradient id="iTCqR8b" x1="23.378" x2="23.378" y1="23.811" y2="20.152" gradientUnits="userSpaceOnUse"><stop class="bjb8jwbqd"/><stop offset=".542" class="bjb8jwbqd"/><stop offset="1" class="rr64x-rjp"/></linearGradient><linearGradient id="iWcPKCe" x1="9.497" x2="9.497" y1="14.556" y2="10.486" gradientUnits="userSpaceOnUse"><stop class="dunu49b1w"/><stop offset="1" class="g0uh0abno"/></linearGradient><linearGradient id="i3tAJ8d" x1="17.666" x2="24.856" y1="16" y2="19.737" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers-dark" /></template>
<style>
.b-jo-_osr {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
}

.bjb8jwbqd {
  stop-color: var(--svg-color--472c33, #472C33);
}

.bmy67tbbi {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
  stop-opacity: 0;
}

.c7owaubke {
  fill: var(--svg-color--4a2c29, #4A2C29);
  d: path("M20.811 2.91c-2.136 2.178-4.64 5.148-5.515 8.632l-.223 2.766h5.03c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.778-.066-4.309c-.43-.367-2.223-1.394-3.8.215");
}

.c87566b7j {
  stop-color: var(--svg-color--3a202f, #3A202F);
}

.cv6x_l7vq {
  stop-color: var(--svg-color--564243, #564243);
  stop-opacity: 0;
}

.d0-at8b1l {
  stop-color: var(--svg-color--372a29, #372A29);
}

.d54yffbyd {
  d: path("M17.827 13.48a2.984 2.984 0 1 0 0 5.968h1.59a1 1 0 0 1 .788.386l2.044 2.621c1.17 1.5 3.578.673 3.578-1.23V19.48a6 6 0 0 0-5.212-5.949a3 3 0 0 0-.554-.051z");
}

.daslsfy7k {
  stroke: var(--svg-color--634f4d, #634F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.73 4.228c2.11 2.245 4.896 6.194 5.22 9.602c.345 3.617.614 6.275.433 7.195");
}

.dunu49b1w {
  stop-color: var(--svg-color--6d524f, #6D524F);
}

.e1qiqxrgs {
  stop-color: var(--svg-color--281815, #281815);
}

.ef9gcs5hx {
  stop-color: var(--svg-color--3f2c2b, #3F2C2B);
}

.fcvrbabtv {
  stop-color: var(--svg-color--200e0d, #200E0D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0c9a_bdy {
  fill: var(--svg-color--4b312d, #4B312D);
  d: path("M5.823 11.663c0-1.43 1.25-2.59 2.79-2.59c1.542 0 2.792 1.16 2.792 2.59v2.383c0 1.43-1.25 2.59-2.791 2.59c-1.542 0-2.791-1.16-2.791-2.59z");
}

.g0uh0abno {
  stop-color: var(--svg-color--6d524f, #6D524F);
  stop-opacity: 0;
}

.ghkwc7bmc {
  fill: var(--svg-color--4b312d, #4B312D);
  d: path("M10.335 10.913c0-1.646 1.27-2.98 2.84-2.98c1.567 0 2.839 1.334 2.839 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.gzpoo_nab {
  stop-color: var(--svg-color--210f0f, #210F0F);
  stop-opacity: 0;
}

.hhasrlbwz {
  stop-color: var(--svg-color--624b48, #624B48);
  stop-opacity: 0;
}

.hhdj75n8v {
  stop-color: var(--svg-color--543b37, #543B37);
}

.i1xzen-dq {
  stop-color: var(--svg-color--17070a, #17070A);
}

.icsq1bbfo {
  stop-color: var(--svg-color--17070a, #17070A);
  stop-opacity: 0;
}

.ipj2k3b_s {
  stop-color: var(--svg-color--483b38, #483B38);
  stop-opacity: 0;
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.jb7vfybqr {
  stop-color: var(--svg-color--55413f, #55413F);
}

.keb3gdc6l {
  width: 1.693px;
  height: 5.457px;
  x: 13.379px;
  y: 9.513px;
  fill: var(--svg-color--6d524f, #6D524F);
  rx: 0.847px;
}

.kf5rkf18z {
  stop-color: var(--svg-color--372a29, #372A29);
  stop-opacity: 0;
}

.ktwiu8bdi {
  fill: var(--svg-color--221013, #221013);
  d: path("M16.842 15.105c-1.732 0-3.136 1.245-3.136 2.782s1.404 2.782 3.136 2.782h1.671c2.525 0 3.18.133 3.379.36l1.536-.178c1.23 1.4.995.652.995-1.123v-.504c0-2.84-1.56-3.712-4.65-4.071a3.5 3.5 0 0 0-.583-.048z");
}

.lm0cklbhu {
  d: path("m6.01 20.82l-.187-5.113v-1.555H20.29c.01-.844-1.843-4.116-4.253-7.32c-1.422-1.891-.62-3.566.515-4.305c1.477-.961 3.219-.25 3.946.898c0 0 5.636 5.93 5.636 13.305c.127 4.64.032 5.397-1.219 7.86c-1.815 3.574-5.716 5.356-9.247 5.356c-5.813 0-9.471-4.138-9.659-9.125");
}

.lz22nac7d {
  stop-color: var(--svg-color--584340, #584340);
  stop-opacity: 0;
}

.m4d8uf0de {
  stop-color: var(--svg-color--503e3a, #503E3A);
}

.mh9054bbp {
  stop-color: var(--svg-color--564243, #564243);
}

.mrg8g156k {
  stop-color: var(--svg-color--40302d, #40302D);
  stop-opacity: 0;
}

.mzjby4bml {
  d: path("M20.125 13.48c1.027.112 3.18.377 4.78 2.76c.886-7.739-4.406-12.815-4.406-12.815c-.727-1.148-2.47-1.86-3.946-.898c-1.135.739-1.937 2.414-.515 4.304c1.979 2.632 3.582 5.308 4.087 6.649");
}

.ny5ybgmod {
  stop-color: var(--svg-color--483b38, #483B38);
}

.o43u81btt {
  stop-color: var(--svg-color--55413f, #55413F);
  stop-opacity: 0;
}

.o463evbal {
  stop-color: var(--svg-color--3f2c2b, #3F2C2B);
  stop-opacity: 0;
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.ooyxpw46h {
  d: path("M20.811 2.91c-2.136 2.178-4.64 5.148-5.515 8.632l-.223 2.766h5.03c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.778-.066-4.309c-.43-.367-2.223-1.394-3.8.215");
}

.p_us1bcmz {
  stop-color: var(--svg-color--3b202d, #3B202D);
  stop-opacity: 0;
}

.p9ifgsbfy {
  fill: var(--svg-color--221013, #221013);
  d: path("M6.375 12.154c0-1.356 1.155-2.456 2.58-2.456c1.424 0 2.578 1.1 2.578 2.456v2.26c0 1.356-1.154 2.456-2.579 2.456c-1.424 0-2.579-1.1-2.579-2.456z");
}

.pcr0x3b6x {
  stop-color: var(--svg-color--281815, #281815);
  stop-opacity: 0;
}

.rr64x-rjp {
  stop-color: var(--svg-color--472c33, #472C33);
  stop-opacity: 0;
}

.rytyi-j4b {
  stop-color: var(--svg-color--200e0d, #200E0D);
}

.s8scx1bpu {
  stop-color: var(--svg-color--261716, #261716);
  stop-opacity: 0;
}

.t-ej0lz2g {
  stop-color: var(--svg-color--584340, #584340);
}

.towbt1bfr {
  stop-color: var(--svg-color--261716, #261716);
}

.ur5n04b0r {
  fill: var(--svg-color--452b32, #452B32);
  d: path("m6.01 20.82l-.187-5.113v-1.555H20.29c.01-.844-1.843-4.116-4.253-7.32c-1.422-1.891-.62-3.566.515-4.305c1.477-.961 3.219-.25 3.946.898c0 0 5.636 5.93 5.636 13.305c.127 4.64.032 5.397-1.219 7.86c-1.815 3.574-5.716 5.356-9.247 5.356c-5.813 0-9.471-4.138-9.659-9.125");
}

.vi1cnkhrt {
  stop-color: var(--svg-color--210f0f, #210F0F);
}

.vjqngfski {
  stop-color: var(--svg-color--503e3a, #503E3A);
  stop-opacity: 0;
}

.vptai38bv {
  stop-color: var(--svg-color--6c5a58, #6C5A58);
  stop-opacity: 0;
}

.vqpc8gbud {
  stop-color: var(--svg-color--6c5a58, #6C5A58);
}

.vzwx6yfqm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.735 16h.615c2.03 0 4.2.587 4.723 2.547c.1.373.175.789.215 1.25");
}

.w-8axdw9p {
  d: path("M10.335 10.913c0-1.646 1.27-2.98 2.84-2.98c1.567 0 2.839 1.334 2.839 2.98v2.743c0 1.646-1.272 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.w9896nonk {
  stop-color: var(--svg-color--3b202d, #3B202D);
}

.wbbh4mb5o {
  stop-color: var(--svg-color--40302d, #40302D);
}

.wvawutbhl {
  width: 1.36px;
  height: 4.484px;
  x: 8.467px;
  y: 10.486px;
  rx: 0.68px;
}

.xepusvbbq {
  d: path("M5.823 11.663c0-1.43 1.25-2.59 2.79-2.59c1.542 0 2.792 1.16 2.792 2.59v2.383c0 1.43-1.25 2.59-2.791 2.59c-1.542 0-2.791-1.16-2.791-2.59z");
}

.xoe2znb0d {
  fill: var(--svg-color--221013, #221013);
  d: path("M9.827 12.913c0-1.349 1.148-2.442 2.564-2.442s2.564 1.093 2.564 2.442v2.246c0 1.349-1.148 2.442-2.564 2.442s-2.564-1.093-2.564-2.441z");
}

.zo8ke71vh {
  stroke: var(--svg-color--64514e, #64514E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.581 4.658c-.929 1.152-1.946 2.62-3.247 4.415");
}

.ztpvcgb-y {
  stop-color: var(--svg-color--624b48, #624B48);
}

</style>
