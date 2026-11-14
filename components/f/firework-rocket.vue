<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rnb7ltlmc"/><path class="ujpz3mcqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firework-rocket" /></template>
<style>
.rnb7ltlmc {
  d: path("m20.394 3.734l-1.06 6.011l-6.011 6.01l-4.95-4.95l6.011-6.01Z");
}

.ujpz3mcqk {
  d: path("m11.202 7.977l-5.303.354l-2.122 2.121l4.243.707Zm4.95 4.95l-.354 5.303l-2.121 2.121l-.707-4.242Zm-7.425 2.475l-3.182 3.182");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
