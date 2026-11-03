<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow154wb2c"/><path clip-rule="evenodd" class="i-7gioi-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:homes-duotone" /></template>
<style>
.i-7gioi-t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.0605 7.711C12.6025 7.2519 13.2897 7 14 7C14.7103 7 15.3975 7.2519 15.9395 7.711L20.9395 11.9473C21.6122 12.5174 22 13.3546 22 14.2364L22 19C22 20.6569 20.6569 22 19 22L9 22C7.3431 22 6 20.6569 6 19L6 14.2364C6 13.3546 6.3878 12.5174 7.0606 11.9473L12.0605 7.711ZM12 20L16 20L16 18C16 16.8954 15.1046 16 14 16C12.8954 16 12 16.8954 12 18L12 20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow154wb2c {
  stroke-opacity: 0.4;
  d: path("M3.1715 12.8116C3.0613 12.5636 3 12.289 3 12L3 7.5417C3 6.9538 3.2586 6.3957 3.7072 6.0157L6.7072 3.474C7.4532 2.842 8.5468 2.842 9.2928 3.474L10.9186 4.8515");
}

</style>
