<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r9xp5bcjg"/><path class="jgwsa2hcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garlic-sharp" /></template>
<style>
.jgwsa2hcy {
  d: path("M10.75 10.25C9 12.5 8.25 16.5 9.5 19.69m3.75-9.44c1.75 2.25 2.5 6.25 1.25 9.44");
}

.r9xp5bcjg {
  d: path("M12 4.25c.5 2 2 3 4 4.25c2.25 1.4 3.75 3.25 3.75 5.75c0 3.4-3.5 5.75-7.75 5.75s-7.75-2.35-7.75-5.75c0-2.5 1.5-4.35 3.75-5.75c2-1.25 3.5-2.25 4-4.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
