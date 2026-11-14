<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0igy46qs"/><path class="vkvbf_b6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certificate-x" /></template>
<style>
.f0igy46qs {
  d: path("M9.8 17.5H2.5V4h19v7.9M6 8.5h5M6 12h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkvbf_b6o {
  d: path("M12.5 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM15 15l3 3m0-3l-3 3");
}

</style>
