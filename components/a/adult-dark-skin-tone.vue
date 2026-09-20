<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mj0wdurlg"/><radialGradient id="SVG4mSBoibJ" cx="95.248" cy="22.384" r="30.469" gradientTransform="matrix(1 0 0 .4912 -12.275 94.62)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG4mSBoibJ)" class="tnixxsb5f"/><radialGradient id="SVGR8Yk3dxb" cx="65.24" cy="26.915" r="9.004" gradientTransform="rotate(154.924 80.09 65.833)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGR8Yk3dxb)" class="bxmcyeh2v"/><radialGradient id="SVGVgxWcb7M" cx="88.575" cy="52.387" r="39.55" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 52.718 167.2)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGVgxWcb7M)" class="jzwfqxilm"/><radialGradient id="SVGUAuKDdrC" cx="38.383" cy="52.387" r="39.55" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 79.056 117.148)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGUAuKDdrC)" class="rjarfit8l"/><radialGradient id="SVGJUAYVddS" cx="45.056" cy="22.384" r="30.469" gradientTransform="matrix(-1 0 0 .4912 90.112 94.62)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGJUAYVddS)" class="ak4s4ihnt"/><radialGradient id="SVGVP9fqdvi" cx="15.047" cy="26.915" r="9.004" gradientTransform="rotate(205.076 9.02 57.178)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGVP9fqdvi)" class="c_4hqgt0m"/><path class="olsxlybtm"/><path class="ammers21d"/><path class="cibuvtbly"/><path class="nhsdmvb5a"/><g class="d2ol71wkq"><ellipse class="xas563fwj"/><ellipse class="lccq-6pww"/></g><path class="eg4q_mbgx"/><path class="qhji4rklz"/><radialGradient id="SVGfwUBwbDB" cx="87.443" cy="73.25" r="46.359" gradientTransform="matrix(.3076 .9515 .706 -.2282 8.83 -11.739)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGfwUBwbDB)" class="t0gocmbuk"/><radialGradient id="SVGsLKAjeIC" cx="42.247" cy="123.799" r="12.155" gradientTransform="matrix(.8813 .4726 .5603 -1.045 -64.35 113.606)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGsLKAjeIC)" class="de6ok1bjv"/><radialGradient id="SVGViD6OdFE" cx="163.601" cy="66.051" r="37.367" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 237.25 55.895)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGViD6OdFE)" class="dc66yzbpl"/><radialGradient id="SVGou3Iyr3k" cx="37.367" cy="112.71" r="11.157" gradientTransform="matrix(1 0 0 -1.2233 0 153.168)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGou3Iyr3k)" class="oq6mg3bed"/><radialGradient id="SVGmCE54rvB" cx="35.831" cy="93.016" r="20.925" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 93.055 -39.766)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGmCE54rvB)" class="e78tg-rwq"/><radialGradient id="SVGqkv6YdbQ" cx="30.867" cy="72.811" r="21.969" gradientTransform="rotate(187.833 -1.612 76.638)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGqkv6YdbQ)" class="ir4s7-bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:adult-dark-skin-tone" /></template>
<style>
.ak4s4ihnt {
  d: path("M64.04 123.36v-12.29l-37.18-2.94l-3.38 4.16s8 11.07 28.92 11.07z");
}

.ammers21d {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 13.15c-22.64 0-43.61 24.21-43.61 59.06C20.39 106.87 42 124 64 124s43.61-17.13 43.61-51.79c0-34.84-20.97-59.06-43.61-59.06");
}

.bxmcyeh2v {
  d: path("M104.46 106.93c-5.57-8.46 6.78-11.61 6.78-11.61l.01.01c-2.15 2.67-3.12 5-1.86 7.29c1.57 2.87 6.26 3.29 6.26 3.29s-6.38 5.68-11.19 1.02");
}

.c_4hqgt0m {
  d: path("M23.57 106.93c5.57-8.46-6.78-11.61-6.78-11.61l-.01.01c2.15 2.67 3.12 5 1.86 7.29c-1.57 2.87-6.26 3.29-6.26 3.29s6.38 5.68 11.19 1.02");
}

.cibuvtbly {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M69.02 87.29a1.6 1.6 0 0 0-.42-.11h-9.2c-.14.02-.28.05-.42.11c-.83.34-1.29 1.2-.9 2.12c.4.92 2.23 3.5 5.92 3.5s5.52-2.58 5.92-3.5s-.06-1.78-.9-2.12");
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.dc66yzbpl {
  d: path("M83.72 5.85c9.52 2.58 14.17 7.42 15.72 13.9c.46 1.9 1 19.62-32.83-.52c-12.58-7.49-9.15-12.18-7.67-12.71c5.75-2.09 14.11-3.56 24.78-.67");
}

.de6ok1bjv {
  d: path("M54.83 8.35c-1.42.69-2.68 1.38-3.77 1.97c-1.25.68-9.33 5.16-14.98 1.95c-3.48-1.98-3.48-7.26-3.47-7.45c-1.6 2.04-6.44 16.63 7.71 17.6c6.1.42 9.87-4.9 12.09-9.41c.81-1.63 2.08-4.02 2.42-4.66");
}

.e78tg-rwq {
  d: path("m31.57 21.81l-6.26-1.01c-.24 0-1.08.08-1.53.14c-3.52.49-7.68 2.31-9.92 6.98c-2.42 5.02-2.35 9.33-1.7 12.21c.19.97.58 2.05.58 2.05s3.1-2.94 10.47-3.13z");
}

.eg4q_mbgx {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M52.29 63.47c-1.2-1.59-3.99-3.91-9.39-3.91s-8.19 2.32-9.39 3.91c-.53.71-.4 1.52-.03 2.01c.34.46 1.35.88 2.47.5s3.3-1.51 6.95-1.53c3.65.03 5.84 1.15 6.95 1.53s2.13-.04 2.47-.5c.37-.49.5-1.3-.03-2.01m42.21 0c-1.2-1.59-3.99-3.91-9.39-3.91s-8.19 2.32-9.39 3.91c-.53.71-.4 1.52-.03 2.01c.34.46 1.35.88 2.47.5s3.3-1.51 6.95-1.53c3.65.03 5.84 1.15 6.95 1.53c1.12.38 2.13-.04 2.47-.5c.36-.49.5-1.3-.03-2.01");
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.ir4s7-bsm {
  d: path("M12.44 42.42c-3.08 2.74-7.24 8.84-4.17 16.4c2.31 5.71 10.53 8.19 10.53 8.19c0 .03 1.64.51 2.49.51l1.92-28.49c-3.94 0-7.72 1.18-10.17 2.88c.02.06-.61.47-.6.51");
}

.jzwfqxilm {
  d: path("M119.45 59.42c5.53 13.47-.29 27.34-5.74 33.19c-.75.8-3.92 3.92-4.64 6.4c0 0-12.42-17.31-16.12-27.49c-.75-2.05-1.43-4.17-1.52-6.35c-.07-1.64.19-3.59 1.13-4.98c1.16-1.71 26.23-2.21 26.23-2.21c0 .02.66 1.44.66 1.44");
}

.lccq-6pww {
  cx: 85.1px;
  cy: 75.23px;
  rx: 6.32px;
  ry: 6.55px;
}

.mj0wdurlg {
  fill: var(--svg-color--232020, #232020);
  d: path("M109.4 102.62c-1.62-2.96.45-5.96 3.98-9.68c5.6-5.91 11.7-19.6 6.04-33.51c.03-.08-1.12-2.42-1.08-2.5l-2.34-.12c-.75-.11-26.36-.16-52-.16s-51.25.05-52 .16c0 0-3.45 2.54-3.42 2.61c-5.66 13.91.44 27.6 6.04 33.51c3.53 3.72 5.6 6.73 3.98 9.68c-1.57 2.87-6.26 3.29-6.26 3.29s1.08 2.94 3.69 4.52c2.41 1.46 5.37 1.81 7.42 1.86c0 0 8 11.07 28.92 11.07h23.28c20.92 0 28.92-11.07 28.92-11.07c2.05-.05 5.01-.39 7.42-1.86c2.61-1.58 3.69-4.52 3.69-4.52s-4.7-.41-6.28-3.28");
}

.nhsdmvb5a {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M74.95 97.71c-4.14 2.46-17.73 2.46-21.87 0c-2.38-1.42-4.81.75-3.82 2.91c.97 2.12 8.38 7.06 14.79 7.06s13.72-4.93 14.7-7.06c.98-2.16-1.42-4.32-3.8-2.91");
}

.olsxlybtm {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M99.55 64.37h-71.1c-7.67 0-13.94 6.68-13.94 14.85s6.27 14.85 13.94 14.85h71.11c7.67 0 13.94-6.68 13.94-14.85s-6.28-14.85-13.95-14.85");
}

.oq6mg3bed {
  d: path("M32.57 4.82c-.02.01-.04.02-.08.03h-.01c-1.21.51-10.73 4.91-7.17 15.94l10.13 1.63C26.48 13.35 32.61 4.8 32.61 4.8z");
}

.qhji4rklz {
  fill: var(--svg-color--232020, #232020);
  d: path("M116.14 31.41c-3.18-4.81-10.29-11.25-16.68-11.67C98.44 13.6 91.86 8.4 85.5 6.38c-17.21-5.45-28.42.66-34.43 3.94c-1.25.68-9.33 5.16-14.98 1.95c-3.54-2.01-3.47-7.46-3.47-7.46s-11.09 4.22-7.3 16c-3.81.16-8.81 1.76-11.45 7.11c-3.15 6.37-2.03 11.7-1.12 14.25c-3.28 2.78-7.4 8.71-4.57 16.4c2.13 5.79 10.63 8.45 10.63 8.45c-.6 10.42 1.34 16.84 2.37 19.43c.18.45.83.41.94-.06c1.28-5.16 5.68-23.15 5.24-26.29c0 0 14.76-2.93 28.84-13.29c2.87-2.11 5.97-3.91 9.27-5.22c17.68-7.04 21.38 4.97 21.38 4.97s12.25-2.35 15.95 14.67c1.39 6.38 2.33 16.59 3.12 23.73c.06.5.74.61.94.14c1.24-2.83 3.71-8.46 4.3-14.19c.21-2.02 5.65-4.69 7.98-13.35c3.14-11.57-.71-22.68-3-26.15");
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.rjarfit8l {
  d: path("M8.58 59.42c-5.52 13.47.29 27.34 5.74 33.19c.75.8 3.92 3.92 4.64 6.4c0 0 12.42-17.31 16.12-27.49c.75-2.05 1.43-4.17 1.52-6.35c.07-1.64-.19-3.59-1.13-4.98c-1.16-1.71-2.51-1.25-4.47-1.25c-3.75 0-20.15-.96-21.42-.96c0 .02-1 1.44-1 1.44");
}

.t0gocmbuk {
  d: path("M111.12 70.95c.21-2.02 5.65-4.69 7.98-13.35c.25-.92.46-1.86.65-2.8c1.9-10.53-1.51-20.19-3.63-23.39c-2.94-4.44-9.24-10.27-15.22-11.46c-.52-.07-1.03-.13-1.51-.16c0 0 .43 2.79-.7 5.02c-1.46 2.89-4.43 3.57-4.43 3.57c15.59 15.59 14.48 28.63 16.86 42.57");
}

.tnixxsb5f {
  d: path("M63.99 123.36v-12.29l37.18-2.94l3.38 4.16s-8 11.07-28.92 11.07z");
}

.xas563fwj {
  cx: 42.9px;
  cy: 75.23px;
  rx: 6.32px;
  ry: 6.55px;
}

</style>
