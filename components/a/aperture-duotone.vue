<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="npfrxrb2t"/><path class="klirv07oh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:aperture-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.klirv07oh {
  d: path("M201.54 54.46A104 104 0 0 0 54.46 201.54A104 104 0 0 0 201.54 54.46m-11.31 11.32a88 88 0 0 1 11 13.48L167.55 119l-27.92-78.22a87.34 87.34 0 0 1 50.6 25M155.59 133l-18.16 21.37l-27.59-5l-9.43-26.37l18.16-21.37l27.59 5ZM65.77 65.78a87.34 87.34 0 0 1 56.66-25.59l17.51 49L58.3 74.32a88 88 0 0 1 7.47-8.54m-19.12 95.76a88.4 88.4 0 0 1 2.53-72.62l51.21 9.35Zm19.12 28.68a88 88 0 0 1-11-13.48L88.45 137l27.92 78.18a87.34 87.34 0 0 1-50.6-24.96m124.46 0a87.34 87.34 0 0 1-56.66 25.59l-17.51-49l81.64 14.91a88 88 0 0 1-7.47 8.5m-34.62-32.49l53.74-63.27a88.4 88.4 0 0 1-2.53 72.62Z");
}

.npfrxrb2t {
  d: path("M195.88 60.12a96 96 0 1 0 0 135.76a96 96 0 0 0 0-135.76m-55.34 103l-36.68-6.69l-12.54-35.13l24.14-28.41l36.68 6.69l12.54 35.12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
