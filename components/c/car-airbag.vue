<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="fz8lsfb2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-airbag" /></template>
<style>
.fz8lsfb2o {
  d: path("M7.5 15c-1.5-2-1-5 1-5.75C9 7 11 6.25 12 7.5c1-1.25 3-.5 3.5 1.75c2 .75 2.5 3.75 1 5.75Zm-5-3h4.25m10.5 0h4.25M12 15v6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
