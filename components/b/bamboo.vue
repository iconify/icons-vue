<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<defs><linearGradient id="SVGPCzgbbCk" x1="50.016%" x2="50.016%" y1="-98.299%" y2="38.217%"><stop offset="0%" class="sav6x4bmf"/><stop offset="100%" class="g_gp7lgqe"/></linearGradient><linearGradient id="SVGIVr8z3Pf" x1="50.016%" x2="50.016%" y1=".763%" y2="138.581%"><stop offset="0%" class="sav6x4bmf"/><stop offset="100%" class="g_gp7lgqe"/></linearGradient></defs><path class="o46s0obsu"/><path fill="url(#SVGPCzgbbCk)" class="fwuwvvb_b"/><path fill="url(#SVGIVr8z3Pf)" class="nb4giub2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bamboo" /></template>
<style>
.fwuwvvb_b {
  d: path("M1.205 184.48c8.45 63.437 62.537 110.83 126.534 110.874v-77.142c-27.809 0-50.37-22.508-50.437-50.316z");
}

.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.nb4giub2b {
  d: path("M0 166.691v1.205h77.302c.066-27.809 22.628-50.317 50.437-50.317l-16.585-75.936C48.145 49.853.767 103.153 0 166.69");
}

.o46s0obsu {
  fill: var(--svg-color--2684ff, #2684ff);
  d: path("M247.206 167.896h-61.4a8.03 8.03 0 0 0-8.032 6.827c-3.487 24.952-24.84 43.511-50.035 43.49l16.625 75.936c60.232-7.87 106.592-57.067 110.873-117.66a8.03 8.03 0 0 0-8.031-8.593m-106.256-1.928l88.346-75.936a8.03 8.03 0 0 0 0-12.047L140.95 1.928a8.031 8.031 0 0 0-13.212 6.103v151.833a8.031 8.031 0 0 0 13.212 6.104");
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

</style>
