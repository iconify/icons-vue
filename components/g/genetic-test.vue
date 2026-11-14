<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d73w7_pqa"/><path class="zb7oitbsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genetic-test" /></template>
<style>
.d73w7_pqa {
  d: path("M5 2.5v15a2.5 2.5 0 0 0 5 0v-15m-6.25 0h7.5M15 3c0 4.5 6 4.5 6 9s-6 4.5-6 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zb7oitbsx {
  d: path("M21 3c0 4.5-6 4.5-6 9s6 4.5 6 9");
}

</style>
