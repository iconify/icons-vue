<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s0xo4d4oj"/><path class="w-8n6wblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-drops-sharp" /></template>
<style>
.s0xo4d4oj {
  d: path("M12 2.75c1.25 1.75 2.75 3.25 2.75 5a2.75 2.75 0 0 1-5.5 0c0-1.75 1.5-3.25 2.75-5ZM2.75 17c2.5-3 5.75-4.25 9.25-4.25S18.75 14 21.25 17c-2.5 3-5.75 4.25-9.25 4.25S5.25 20 2.75 17Z");
}

.w-8n6wblp {
  d: path("M12 15.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 1 1 0-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
