<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hqd2zab-n"/><path class="z_ldbs8uo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contactless-sharp" /></template>
<style>
.hqd2zab-n {
  d: path("M5 9.25a5 5 0 0 1 0 5.5M8.5 7a8 8 0 0 1 0 10M12 4.75a11 11 0 0 1 0 14.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_ldbs8uo {
  d: path("M15.5 2.75a13.5 13.5 0 0 1 0 18.5");
}

</style>
