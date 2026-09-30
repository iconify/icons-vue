<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kytdc0isv"/><path clip-rule="evenodd" class="mymd70bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-check-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kytdc0isv {
  d: path("M15.8284 5L15.8284 2L2 2L2 15.8284L5 15.8284");
}

.mymd70bam {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L22 7C22.5523 7 23 7.4477 23 8L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7ZM12.4142 14L11 15.4142L13.2929 17.7071C13.4804 17.8946 13.7348 18 14 18C14.2652 18 14.5196 17.8946 14.7071 17.7071L19 13.4142L17.5858 12L14 15.5858L12.4142 14Z");
  stroke: none;
}

</style>
