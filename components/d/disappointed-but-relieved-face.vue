<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<symbol id="ssvg-id-disappointed-but-relieved-faced" viewBox="-64.5 -64.5 129 129"><g class="bqzt8ngox"><path class="nes8vjytg"/><path class="o2qzm0b0x"/><path class="ytyxx4q3b"/><path class="htano6txl"/><path class="hglg8acvx"/><path class="t49x-q1ug"/><path class="fzv3msbsm"/><path class="j7_d0nbzc"/></g></symbol><linearGradient id="ssvg-id-disappointed-but-relieved-facea" x1="64" x2="64" y1="19.717" y2="107.7" gradientUnits="userSpaceOnUse"><stop offset=".438" class="qu1llccgx"/><stop offset=".637" class="a-as8x3yf"/><stop offset=".806" class="fz3g4dfob"/><stop offset=".917" class="rsmbf9bdq"/></linearGradient><path fill="url(#ssvg-id-disappointed-but-relieved-facea)" class="z5pvlv0ga"/><path class="mk3s0l27t"/><g class="fhx_r0u3j"><path class="pr51vqbwh"/><path class="k81kodbzh"/></g><path class="czlq4s63y"/><path class="ozfg057pu"/><path class="pcot-8bzl"/><path class="ztwjtvbuy"/><path class="j10whybkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:disappointed-but-relieved-face" /></template>
<style>
.a-as8x3yf {
  stop-color: var(--svg-color--fac42c, #FAC42C);
}

.bqzt8ngox {
  fill: none;
  stroke: var(--svg-color--4285f4, #4285F4);
  stroke-miterlimit: 10;
}

.czlq4s63y {
  d: path("M24 88.99c-5.64 0-10.01-5.51-10.01-10.25 0-3.29 1.46-7.07 3.48-12.31.29-.76.6-1.55.91-2.37 1.59-4.19 3.9-8.7 5.5-11.67 1.41 2.92 3.52 7.34 5.5 11.77 3.59 8.06 4.63 11.33 4.63 14.58 0 4.74-4.37 10.25-10.01 10.25z");
  fill: var(--svg-color--5f7aff, #5F7AFF);
}

.fhx_r0u3j {
  fill: var(--svg-color--6d4c41, #6D4C41);
}

.fz3g4dfob {
  stop-color: var(--svg-color--fdd931, #FDD931);
}

.fzv3msbsm {
  d: path("M15.99 48.91v-97.84");
}

.hglg8acvx {
  d: path("M-.01 51V-51");
}

.htano6txl {
  d: path("M0-43c-12.29 0-23.54 3.94-31.68 11.09C-40.39-24.25-45-13.21-45 0c0 29.7 22.6 43 45 43 21.67 0 45-13.46 45-43S21.67-43 0-43z");
}

.j10whybkg {
  d: path("M83.33 44.19c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42 8-3.54 8-9.42-3.81-9.42-8-9.42z");
  fill: var(--svg-color--242424, #242424);
}

.j7_d0nbzc {
  d: path("M53 .08H-53");
}

.k81kodbzh {
  d: path("M95.53 28.04c-.36-1.12-1.35-1.86-2.54-1.89-3.28-.14-6.53-1.74-8.67-4.3-.86-1.07-2.3-1.37-3.45-.75-1.11.59-1.59 1.8-1.21 3.01.05.16.12.32.2.48a12.64 12.64 0 0 0 2.73 3.43c2.95 2.65 6.99 3.9 10.8 3.34.85-.14 1.51-.57 1.91-1.21.37-.62.46-1.39.23-2.11z");
}

.mk3s0l27t {
  d: path("M64 10.11c14.99 0 28.86 4.95 39.03 13.93C114.13 33.83 120 47.65 120 64c0 16.27-5.87 30.07-16.97 39.89-10.21 9.03-24.07 14-39.03 14-15.04 0-28.9-4.91-39.04-13.82C13.86 94.32 8 80.46 8 64c0-16.54 5.86-30.42 16.96-40.15C35.07 14.99 48.93 10.11 64 10.11m0-4c-31.15 0-60 20-60 57.89 0 37.68 28.85 57.89 60 57.89s60-20.73 60-57.89c0-37.37-28.85-57.89-60-57.89z");
  fill: var(--svg-color--eb8f00, #EB8F00);
}

.nes8vjytg {
  d: path("M-64-64H64V64H-64z");
}

.o2qzm0b0x {
  d: path("M36.95 37.82C27.32 46.32 14.2 51 0 51c-14.27 0-27.39-4.62-36.96-13.01C-47.45 28.79-53 15.65-53 0c0-15.58 5.55-28.69 16.04-37.92C-27.36-46.35-14.24-51 0-51c14.17 0 27.29 4.71 36.95 13.25C47.45-28.45 53-15.4 53 0c0 15.47-5.55 28.55-16.05 37.82z");
}

.ozfg057pu {
  d: path("M23.8 56.86c1.16 2.44 2.48 5.28 3.75 8.12 3.46 7.76 4.46 10.85 4.46 13.76 0 3.74-3.57 8.25-8.01 8.25s-8.01-4.51-8.01-8.25c0-2.92 1.4-6.55 3.34-11.59.3-.77.6-1.56.91-2.38 1.02-2.67 2.34-5.48 3.56-7.91m.2-8.78s-4.74 8.04-7.49 15.26c-2.51 6.6-4.52 11.22-4.52 15.39 0 5.96 5.38 12.25 12.01 12.25s12.01-6.29 12.01-12.25c0-3.75-1.21-7.34-4.81-15.39-3.43-7.7-7.2-15.26-7.2-15.26z");
  fill: var(--svg-color--4864ed, #4864ED);
}

.pcot-8bzl {
  d: path("M64 78.56c11.99 0 20.54 6.22 23.11 10.14.99 1.51 1.19 3.16.52 4.39-.5.93-1.42 1.47-2.51 1.47-.37 0-.75-.06-1.13-.18-6.04-1.89-12.97-2.89-20.03-2.89-7.02 0-13.92 1-19.94 2.89-.39.12-.77.18-1.13.18-1.09 0-2.01-.54-2.51-1.47-.67-1.24-.47-2.88.52-4.39 2.56-3.92 11.11-10.14 23.1-10.14z");
  fill: var(--svg-color--242424, #242424);
}

.pr51vqbwh {
  d: path("M32.47 28.04c.36-1.12 1.35-1.86 2.54-1.89 3.28-.14 6.53-1.74 8.67-4.3.86-1.07 2.3-1.37 3.45-.75 1.11.59 1.59 1.8 1.21 3.01-.05.16-.12.32-.2.48a12.64 12.64 0 0 1-2.73 3.43c-2.95 2.65-6.99 3.9-10.8 3.34-.85-.14-1.51-.57-1.91-1.21-.37-.62-.46-1.39-.23-2.11z");
}

.qu1llccgx {
  stop-color: var(--svg-color--f6a323, #F6A323);
}

.rsmbf9bdq {
  stop-color: var(--svg-color--fee133, #FEE133);
}

.t49x-q1ug {
  d: path("M-16 48.95v-97.88");
}

.ytyxx4q3b {
  d: path("M0 55c-29.59 0-57-19.01-57-55 0-35.8 27.41-55 57-55S57-35.31 57 0c0 35.51-27.41 55-57 55z");
}

.z5pvlv0ga {
  d: path("M64 119.89C36.07 119.89 6 102.4 6 64S36.07 8.11 64 8.11c15.48 0 29.81 5.12 40.36 14.43C115.9 32.72 122 47.06 122 64c0 16.86-6.1 31.17-17.64 41.39-10.58 9.35-24.91 14.5-40.36 14.5z");
}

.ztwjtvbuy {
  d: path("M44.67 44.19c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42 8-3.54 8-9.42-3.81-9.42-8-9.42z");
  fill: var(--svg-color--242424, #242424);
}

</style>
