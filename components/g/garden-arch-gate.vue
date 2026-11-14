<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7dbyrb5g"/><path class="w57jhsx-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-arch-gate" /></template>
<style>
.k7dbyrb5g {
  d: path("M4 21.5V10a8 8 0 0 1 16 0v11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w57jhsx-a {
  d: path("M7 21.5V11a5 5 0 0 1 10 0v10.5M12 6v15.5m-1.5-7h3");
}

</style>
