<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tolgqbnqe"/><path class="sg49t9bza"/><path fill="url(#SVGI7Jh0cYi)" class="ctcw1-sjx"/><path class="wfdhvnban"/><path class="zzyff8ocs"/><defs><linearGradient id="SVGI7Jh0cYi" x1="6.351" x2="24.905" y1="6.122" y2="27.431" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dnxc" /></template>
<style>
.ctcw1-sjx {
  d: path("M3 21v-4.16h1.188V14.4H4.8v-1.2H6v-2.4h1.2v-3h1.2V6.6h1.2V5.4h4.2v1.2H15v1.2h2.4V9h1.2v3h-3v-1.2h-2.4V12h1.2v1.2h1.2v1.2h1.2v1.2h-3.6v-1.2H12v-1.2h-1.2v1.2H9.6v1.8H12v1.2h1.2v1.2h-2.4v-1.2H8.4V21z");
}

.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.sg49t9bza {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M4.2 19.799H15v-1.2h1.2v-1.2h1.2v-1.2h1.2v-1.2h1.2v-6h-1.2v-1.2h-1.2v-1.2h-1.2v-1.2H15v-1.2H9v1.2H7.8v1.2H6.6v1.2H5.4v1.2H4.2z");
}

.tolgqbnqe {
  fill: var(--svg-color--e97e00, #e97e00);
  d: path("M3 21h13.2v-1.2h1.2v-1.2h1.2v-1.2h1.2v-1.2H21V7.8h-1.2V6.6h-1.2V5.4h-1.2V4.2h-1.2V3H7.8v1.2H6.6v1.2H5.4v1.2H4.2v1.2H3z");
}

.wfdhvnban {
  fill: var(--svg-color--6c6c6c, #6c6c6c);
  d: path("M16.2 9.599v1.2h1.2v-1.2z");
}

.zzyff8ocs {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.2v1.2h1.2V7.2z");
}

</style>
