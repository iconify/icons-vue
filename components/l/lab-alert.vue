<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lxr8txb5f"/><path class="bp7e4-djc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-alert" /></template>
<style>
.bp7e4-djc {
  d: path("M15 6V3h2v4.75M8.75 7.5V10l-2.5 4h7l-2.5-4V7.5M18 14.75v3.5M18 21h.01");
}

.lxr8txb5f {
  d: path("M15.16 19.5H3v-10l8-7l8 7v2.44");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
