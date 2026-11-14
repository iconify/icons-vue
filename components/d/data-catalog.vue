<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ua4t_hbzu"/><path class="z5g3tqy0m"/><path class="nynzlpb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-catalog" /></template>
<style>
.nynzlpb7q {
  d: path("M14.75 15.25v5c0 .75 1.5 1.25 3.25 1.25s3.25-.5 3.25-1.25v-5");
}

.ua4t_hbzu {
  d: path("M21.5 11.653V4.5C17 4 14 4.5 12 6c-2-1.5-5-2-9.5-1.5v14c4.462-.496 7.449-.008 9.449 1.462M12 6v6.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5g3tqy0m {
  d: path("M14.75 15.25a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0Z");
}

</style>
