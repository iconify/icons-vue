<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGEG30kbZK" cx="223.589" cy="229.244" r="170.886" gradientTransform="matrix(.73143 0 0 .76142 -36.884 -43.78)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="lszn51bjz"/><stop offset=".828" class="lsnya78sn"/></radialGradient><radialGradient id="SVG1x9xkeNY" cx="223.589" cy="229.244" r="170.886" gradientTransform="matrix(0 .73143 -.76142 0 299.78 -36.884)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="tl19bebav"/><stop offset=".828" class="nfz_c-znm"/></radialGradient><radialGradient id="SVGK7M5xc0s" cx="223.589" cy="229.244" r="170.886" gradientTransform="matrix(-.73143 0 0 -.76142 292.884 299.78)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="qg07eg0tu"/><stop offset=".828" class="m3pwewbxb"/></radialGradient><radialGradient id="SVGuAtGCePs" cx="223.589" cy="229.244" r="170.886" gradientTransform="matrix(0 -.73143 .76142 0 -43.78 292.884)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ojiqvvdih"/><stop offset=".828" class="w8az6stvk"/></radialGradient></defs><path fill="url(#SVGEG30kbZK)" class="vyfqkgbyc"/><path fill="url(#SVG1x9xkeNY)" class="fm5v5ibcg"/><path fill="url(#SVGK7M5xc0s)" class="mp6e-98vo"/><path fill="url(#SVGuAtGCePs)" class="xpyc1_7bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-photos" /></template>
<style>
.fm5v5ibcg {
  d: path("M64 58.222c35.328 0 64 28.672 64 64V128H5.778C2.56 128 0 125.367 0 122.222c0-35.328 28.672-64 64-64");
}

.lsnya78sn {
  stop-color: var(--svg-color--00b054, #00b054);
}

.lszn51bjz {
  stop-color: var(--svg-color--7acaff, #7acaff);
}

.m3pwewbxb {
  stop-color: var(--svg-color--ff4041, #ff4041);
}

.mp6e-98vo {
  d: path("M197.778 64c0 35.328-28.672 64-64 64H128V5.778C128 2.56 130.633 0 133.778 0c35.328 0 64 28.672 64 64");
}

.nfz_c-znm {
  stop-color: var(--svg-color--feca01, #feca01);
}

.ojiqvvdih {
  stop-color: var(--svg-color--aaa7ff, #aaa7ff);
}

.qg07eg0tu {
  stop-color: var(--svg-color--ff81d0, #ff81d0);
}

.tl19bebav {
  stop-color: var(--svg-color--fded1c, #fded1c);
}

.vyfqkgbyc {
  d: path("M58.222 192c0-35.328 28.672-64 64-64H128v122.222c0 3.218-2.633 5.778-5.778 5.778c-35.328 0-64-28.672-64-64");
}

.w8az6stvk {
  stop-color: var(--svg-color--2f89ff, #2f89ff);
}

.xpyc1_7bj {
  d: path("M192 197.778c-35.328 0-64-28.672-64-64V128h122.222c3.218 0 5.778 2.633 5.778 5.778c0 35.328-28.672 64-64 64");
}

</style>
