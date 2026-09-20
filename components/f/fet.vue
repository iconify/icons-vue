<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG97F7wYvD)" class="vf208gx6l"/><defs><linearGradient id="SVG97F7wYvD" x1="6.349" x2="24.905" y1="6.121" y2="27.435" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fet" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.vf208gx6l {
  d: path("M3 3h2.25v2.25H3zm5.625 0h2.25v2.25h-2.25zm0 5.625h2.25v2.25h-2.25zM14.25 3h2.25v2.25h-2.25zm5.625.563H21v1.124h-1.125zm0 5.624H21v1.126h-1.125zm-5.062 0h1.124v1.126h-1.124zm0 5.625h1.124v1.126h-1.124zm-5.626 0h1.126v1.126H9.187zm-5.624 5.063h1.124V21H3.562zm5.624 0h1.126V21H9.187zm5.626 0h1.124V21h-1.124zm5.062 0H21V21h-1.125zm0-5.063H21v1.126h-1.125zM3 8.625h2.25v2.25H3zm0 5.625h2.25v2.25H3z");
}

</style>
