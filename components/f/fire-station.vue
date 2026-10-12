<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wcklgubij"/><path class="xe_x1lpom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wcklgubij {
  d: path("m4.27 8.52l6.71-4.79q1.02-.73 2.04 0l6.71 4.79q1.02.73 1.02 1.98V20q0 1.25-1.25 1.25h-15q-1.25 0-1.25-1.25v-9.5q0-1.25 1.02-1.98");
}

.xe_x1lpom {
  d: path("M12 9.5c.5 2 3.25 3 3.25 5.75a3.25 3.25 0 0 1-6.5 0c0-1.5.75-2.5 1.75-3.25c0 1 .5 1.5 1 1.5c0-1.5-.25-2.5.5-4");
}

</style>
