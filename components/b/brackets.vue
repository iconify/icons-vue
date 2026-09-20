<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><filter id="SVGY50hHbaP" width="200%" height="200%" x="-50%" y="-50%" filterUnits="objectBoundingBox"><feOffset dy="2" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="2"/><feColorMatrix in="shadowBlurOuter1" result="shadowMatrixOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.273992301 0"/><feMerge><feMergeNode in="shadowMatrixOuter1"/><feMergeNode in="SourceGraphic"/></feMerge></filter><linearGradient id="SVGv4VoW5fy" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" class="qbbtv9x_n"/><stop offset="47.57%" class="z0smlybxn"/><stop offset="66.39%" class="bqgdu2b7u"/><stop offset="80.12%" class="xlp8n6bss"/><stop offset="91.3%" class="w3-l24b5o"/><stop offset="100%" class="womvvp5cg"/></linearGradient></defs><path class="rlt5_jb5l"/><path class="ghqdqvbgk"/><path fill="url(#SVGv4VoW5fy)" class="kq92fob8e"/><g class="on3_pzp_l"><path filter="url(#SVGY50hHbaP)" transform="translate(56.32 53.76)" class="yovz7_b3h"/><path filter="url(#SVGY50hHbaP)" transform="translate(56.32 53.76)" class="yc0tkht-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:brackets" /></template>
<style>
.bqgdu2b7u {
  stop-color: var(--svg-color--23a2dc, #23a2dc);
}

.ghqdqvbgk {
  fill: var(--svg-color--fff, #fff);
  d: path("M204.8 28.16c12.705 0 23.04 10.335 23.04 23.04v128c0 12.705-10.335 23.04-23.04 23.04H51.2c-12.705 0-23.04-10.335-23.04-23.04v-128c0-12.705 10.335-23.04 23.04-23.04z");
}

.kq92fob8e {
  d: path("M204.8 28.16c12.705 0 23.04 10.335 23.04 23.04v128c0 12.705-10.335 23.04-23.04 23.04H51.2c-12.705 0-23.04-10.335-23.04-23.04v-128c0-12.705 10.335-23.04 23.04-23.04zm0-28.16H51.2C23.04 0 0 23.04 0 51.2v128c0 28.16 23.04 51.2 51.2 51.2h153.6c28.16 0 51.2-23.04 51.2-51.2v-128C256 23.04 232.96 0 204.8 0");
}

.on3_pzp_l {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
}

.qbbtv9x_n {
  stop-color: var(--svg-color--29abe2, #29abe2);
}

.rlt5_jb5l {
  fill: var(--svg-color--115a91, #115a91);
  d: path("M256 204.8c0 28.16-23.04 51.2-51.2 51.2H51.2C23.04 256 0 232.96 0 204.8V51.2C0 23.04 23.04 0 51.2 0h153.6C232.96 0 256 23.04 256 51.2z");
}

.w3-l24b5o {
  stop-color: var(--svg-color--0e85c9, #0e85c9);
}

.womvvp5cg {
  stop-color: var(--svg-color--0071bc, #0071bc);
}

.xlp8n6bss {
  stop-color: var(--svg-color--1a96d4, #1a96d4);
}

.yc0tkht-d {
  d: path("M64 0v28.16H28.16v64H64v30.72H0V0z");
}

.yovz7_b3h {
  d: path("M143.36 0v122.88h-64V92.16h35.84v-64H79.36V0z");
}

.z0smlybxn {
  stop-color: var(--svg-color--28a9e1, #28a9e1);
}

</style>
