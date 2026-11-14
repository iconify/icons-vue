<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6cgaw80h"/><path class="yos_yvblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kiss-and-ride" /></template>
<style>
.j6cgaw80h {
  d: path("M3 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-.5 15.5v-7a3 3 0 0 1 6 0v7m2.75-3.5v-4l1.75-.75l1.5-3.75h4.25l1.5 3.75l1.25.75v4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yos_yvblu {
  d: path("M12 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
