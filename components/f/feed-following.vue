<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fo19lebgd"/><path class="t_3f_s-ax"/><path class="kqdeg4b0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feed-following" /></template>
<style>
.fo19lebgd {
  d: path("M6 5.5v-1a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v11");
}

.kqdeg4b0x {
  d: path("M7.75 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1.25 8.5c0-2.25 1.5-3.5 3.5-3.5s3.5 1.25 3.5 3.5");
}

.t_3f_s-ax {
  d: path("M2.5 5.5h15V22h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
