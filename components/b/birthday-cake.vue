<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yj5n5kpjo"/><path class="odv024bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-cake" /></template>
<style>
.odv024bxy {
  d: path("M3.5 15q2.5 2 5 0t5 0t7 0M8 11.5V8m4 3.5V8m4 3.5V8M8 5.5h.01m3.99 0h.01m3.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yj5n5kpjo {
  d: path("M3.5 11.5h17v9h-17Z");
}

</style>
