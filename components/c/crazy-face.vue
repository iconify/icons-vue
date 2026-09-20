<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<symbol id="ssvg-id-crazy-facef" viewBox="-64.5 -64.5 129 129"><g class="bqzt8ngox"><path class="nes8vjytg"/><path class="o2qzm0b0x"/><path class="ytyxx4q3b"/><path class="htano6txl"/><path class="hglg8acvx"/><path class="t49x-q1ug"/><path class="fzv3msbsm"/><path class="j7_d0nbzc"/></g></symbol><linearGradient id="ssvg-id-crazy-facea" x1="64" x2="64" y1="19.717" y2="107.7" gradientUnits="userSpaceOnUse"><stop offset=".5" class="rsmbf9bdq"/><stop offset=".612" class="p0_jflzej"/><stop offset=".708" class="xj6qgfb6d"/><stop offset=".797" class="uxvedvbhm"/><stop offset=".883" class="qnth-c2kd"/><stop offset=".9" class="qu1llccgx"/></linearGradient><path fill="url(#ssvg-id-crazy-facea)" class="z5pvlv0ga"/><path class="mk3s0l27t"/><circle class="kmydmcb0v"/><path class="ug3pn5buq"/><path class="mvo0ybnlh"/><circle class="b4_o-iq3a"/><path class="kiia1ez3v"/><path class="xq8x2cc2j"/><path class="trnoj2gxg"/><path class="g9oeepbxg"/><defs><path id="ssvg-id-crazy-faceb" class="x3y7cgbyn"/></defs><clipPath id="ssvg-id-crazy-facec"><use xlink:href="#ssvg-id-crazy-faceb"/></clipPath><path clip-path="url(#ssvg-id-crazy-facec)" class="gktx-ubvl"/><path clip-path="url(#ssvg-id-crazy-facec)" class="szqdvabkz"/><path clip-path="url(#ssvg-id-crazy-facec)" class="wo6m5bepv"/><path clip-path="url(#ssvg-id-crazy-facec)" class="qjm9_ubmv"/><path clip-path="url(#ssvg-id-crazy-facec)" class="ibdp3bc7u"/><path clip-path="url(#ssvg-id-crazy-facec)" class="u3u8cw-aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:crazy-face" /></template>
<style>
.b4_o-iq3a {
  cx: 91.23px;
  cy: 50.98px;
  r: 14.5px;
  fill: var(--svg-color--fff, #fff);
}

.bqzt8ngox {
  fill: none;
  stroke: var(--svg-color--4285f4, #4285F4);
  stroke-miterlimit: 10;
}

.fzv3msbsm {
  d: path("M15.99 48.91v-97.84");
}

.g9oeepbxg {
  d: path("M92.53 79.62c5.5 0 9.98 4.48 9.98 9.98v.66c0 5.5-4.48 9.98-9.98 9.98H35.47c-5.5 0-9.98-4.48-9.98-9.98v-.66c0-5.5 4.48-9.98 9.98-9.98h57.06m0-4H35.47c-7.69 0-13.98 6.29-13.98 13.98v.66c0 7.69 6.29 13.98 13.98 13.98h57.06c7.69 0 13.98-6.29 13.98-13.98v-.66c0-7.69-6.29-13.98-13.98-13.98z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.gktx-ubvl {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M16.4 89.93h95.2");
}

.hglg8acvx {
  d: path("M-.01 51V-51");
}

.htano6txl {
  d: path("M0-43c-12.29 0-23.54 3.94-31.68 11.09C-40.39-24.25-45-13.21-45 0c0 29.7 22.6 43 45 43 21.67 0 45-13.46 45-43S21.67-43 0-43z");
}

.ibdp3bc7u {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M78.25 74.66v30.53");
}

.j7_d0nbzc {
  d: path("M53 .08H-53");
}

.kiia1ez3v {
  d: path("M91.23 40.48c5.79 0 10.5 4.71 10.5 10.5s-4.71 10.5-10.5 10.5-10.5-4.71-10.5-10.5 4.71-10.5 10.5-10.5m0-4c-8.01 0-14.5 6.49-14.5 14.5s6.49 14.5 14.5 14.5 14.5-6.49 14.5-14.5-6.49-14.5-14.5-14.5z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.kmydmcb0v {
  cx: 45.64px;
  cy: 47.98px;
  r: 24.5px;
  fill: var(--svg-color--fff, #fff);
}

.mk3s0l27t {
  d: path("M64 10.11c14.99 0 28.86 4.95 39.03 13.93C114.13 33.83 120 47.65 120 64c0 16.27-5.87 30.07-16.97 39.89-10.21 9.03-24.07 14-39.03 14-15.04 0-28.9-4.91-39.04-13.82C13.86 94.32 8 80.46 8 64c0-16.54 5.86-30.42 16.96-40.15C35.07 14.99 48.93 10.11 64 10.11m0-4c-31.15 0-60 20-60 57.89 0 37.68 28.85 57.89 60 57.89s60-20.73 60-57.89c0-37.37-28.85-57.89-60-57.89z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.mvo0ybnlh {
  d: path("M45.64 38.93c-4.92 0-8.91 2.92-8.91 9.05s3.99 9.05 8.91 9.05 8.91-2.92 8.91-9.05-3.98-9.05-8.91-9.05z");
  fill: var(--svg-color--242424, #242424);
}

.nes8vjytg {
  d: path("M-64-64H64V64H-64z");
}

.o2qzm0b0x {
  d: path("M36.95 37.82C27.32 46.32 14.2 51 0 51c-14.27 0-27.39-4.62-36.96-13.01C-47.45 28.79-53 15.65-53 0c0-15.58 5.55-28.69 16.04-37.92C-27.36-46.35-14.24-51 0-51c14.17 0 27.29 4.71 36.95 13.25C47.45-28.45 53-15.4 53 0c0 15.47-5.55 28.55-16.05 37.82z");
}

.p0_jflzej {
  stop-color: var(--svg-color--fede32, #FEDE32);
}

.qjm9_ubmv {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M64.51 74.66v30.53");
}

.qnth-c2kd {
  stop-color: var(--svg-color--f7a924, #F7A924);
}

.qu1llccgx {
  stop-color: var(--svg-color--f6a323, #F6A323);
}

.rsmbf9bdq {
  stop-color: var(--svg-color--fee133, #FEE133);
}

.szqdvabkz {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M37.02 74.66v30.53");
}

.t49x-q1ug {
  d: path("M-16 48.95v-97.88");
}

.trnoj2gxg {
  d: path("M35.47 102.24c-6.6 0-11.98-5.37-11.98-11.98v-.66c0-6.6 5.37-11.98 11.98-11.98h57.06c6.6 0 11.98 5.37 11.98 11.98v.66c0 6.6-5.37 11.98-11.98 11.98H35.47z");
  fill: var(--svg-color--fff, #fff);
}

.u3u8cw-aq {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M92 74.66v30.53");
}

.ug3pn5buq {
  d: path("M45.64 27.48c11.3 0 20.5 9.2 20.5 20.5s-9.2 20.5-20.5 20.5-20.5-9.2-20.5-20.5 9.2-20.5 20.5-20.5m0-4c-13.53 0-24.5 10.97-24.5 24.5s10.97 24.5 24.5 24.5 24.5-10.97 24.5-24.5-10.96-24.5-24.5-24.5z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.uxvedvbhm {
  stop-color: var(--svg-color--fac12b, #FAC12B);
}

.wo6m5bepv {
  fill: none;
  stroke: var(--svg-color--b3b3b0, #B3B3B0);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4-437px, 4.437px);
  d: path("M50.76 74.66v30.53");
}

.x3y7cgbyn {
  d: path("M93.86 79.67c4.76 0 8.64 4.6 8.64 10.25s-3.87 10.25-8.64 10.25H34.14c-4.76 0-8.64-4.6-8.64-10.25s3.87-10.25 8.64-10.25h59.72");
}

.xj6qgfb6d {
  stop-color: var(--svg-color--fcd32f, #FCD32F);
}

.xq8x2cc2j {
  d: path("M91.23 45.83c-2.8 0-5.07 1.66-5.07 5.16 0 3.49 2.27 5.16 5.07 5.16s5.07-1.66 5.07-5.16-2.27-5.16-5.07-5.16z");
  fill: var(--svg-color--242424, #242424);
}

.ytyxx4q3b {
  d: path("M0 55c-29.59 0-57-19.01-57-55 0-35.8 27.41-55 57-55S57-35.31 57 0c0 35.51-27.41 55-57 55z");
}

.z5pvlv0ga {
  d: path("M64 119.89C36.07 119.89 6 102.4 6 64S36.07 8.11 64 8.11c15.48 0 29.81 5.12 40.36 14.43C115.9 32.72 122 47.06 122 64c0 16.86-6.1 31.17-17.64 41.39-10.58 9.35-24.91 14.5-40.36 14.5z");
}

</style>
