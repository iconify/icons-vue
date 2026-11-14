<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qlnlfob5e"/><path class="qfi76c80d"/><path class="pi_3pdbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:batch-transaction" /></template>
<style>
.pi_3pdbah {
  d: path("M8.5 4h11a2 2 0 0 1 2 2v8M9 10v10");
}

.qfi76c80d {
  d: path("M5.5 7h11a2 2 0 0 1 2 2v8");
}

.qlnlfob5e {
  d: path("M2.5 10h13v10h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
