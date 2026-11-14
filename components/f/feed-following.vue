<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fo19lebgd"/><path class="w4tiy3bfp"/><path class="j_k9md70i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feed-following" /></template>
<style>
.fo19lebgd {
  d: path("M6 5.5v-1a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_k9md70i {
  d: path("M7.75 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.25 8.5c0-2.25 1.5-3.5 3.5-3.5s3.5 1.25 3.5 3.5");
}

.w4tiy3bfp {
  d: path("M6 5.5h8A3.5 3.5 0 0 1 17.5 9v9.5A3.5 3.5 0 0 1 14 22H6a3.5 3.5 0 0 1-3.5-3.5V9A3.5 3.5 0 0 1 6 5.5");
}

</style>
