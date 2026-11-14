<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zh69_0rsg"/><path class="acdje_ocb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claw-machine" /></template>
<style>
.acdje_ocb {
  d: path("M9.25 15.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh69_0rsg {
  d: path("M12 2.5v2M9 10L8 7.75l4-3.25l4 3.25L15 10M4 14v5.5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V14");
}

</style>
