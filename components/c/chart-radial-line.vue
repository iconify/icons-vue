<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="spvcd8b_b"/><path class="a4p6wkbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-radial-line" /></template>
<style>
.a4p6wkbzl {
  d: path("m12 5.75l3.75 5V17L10 14.75L7 10.5Z");
}

.spvcd8b_b {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm9 0V5.75M12 12l6-2m-6 2l3.75 5M12 12l-3.75 5M12 12l-6-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
