<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpzx2kn9r"/><path class="e14-ubb7y"/><path class="f0oho4boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:iv-drip" /></template>
<style>
.e14-ubb7y {
  fill: currentColor;
  d: path("M12 7.75c.75 1 1.25 1.5 1.25 2.25s-.5 1.25-1.25 1.25s-1.25-.5-1.25-1.25s.5-1.25 1.25-2.25Z");
}

.f0oho4boy {
  d: path("M7.5 13.25h9M12 16v5.5");
}

.hpzx2kn9r {
  d: path("M7.5 5.5h9V16h-9Zm4.5-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
