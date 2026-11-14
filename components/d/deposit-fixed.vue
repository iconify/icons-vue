<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qzfv9nbee"/><path class="mt3b3ykjd"/><path class="igbj2lb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-fixed" /></template>
<style>
.igbj2lb_o {
  d: path("M13.75 12.75c-.25-.75-.75-1-1.75-1c-1.25 0-1.75.5-1.75 1.5c0 1.5 3.5.75 3.5 3c0 1-.75 1.5-1.75 1.5s-1.75-.25-1.75-1M12 10.5v1.25m0 6V19");
}

.mt3b3ykjd {
  d: path("M5.25 14.75a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0Z");
}

.qzfv9nbee {
  d: path("M7.5 9.75v-3a4.5 4.5 0 0 1 9 0v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
