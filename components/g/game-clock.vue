<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ttrwiabng"/><path class="h8jv5bbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-clock" /></template>
<style>
.h8jv5bbog {
  d: path("M12 13.5v-5a5 5 0 0 1 5 5Z");
}

.ttrwiabng {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm5.5-11h5m-2.5 0v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
