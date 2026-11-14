<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw2j_fbcl"/><path class="u7nj80b6z"/><path class="njvzl5cqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-replay" /></template>
<style>
.njvzl5cqf {
  d: path("M13.5 7.25L12 8.75l1.5 1.5");
}

.u7nj80b6z {
  d: path("M12 8.75a3.75 3.75 0 1 1-3.75 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw2j_fbcl {
  d: path("M3.5 4.5h17a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-13a1 1 0 0 1 1-1Z");
}

</style>
