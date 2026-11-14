<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezvgvhzgh"/><path class="tl4qwzjft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-pin" /></template>
<style>
.ezvgvhzgh {
  d: path("M12.273 17.482c-2.003.834-4.355 1.268-7.023 1.268c0-9.5 5.5-15 15-15c0 2.68-.438 5.041-1.279 7.051M3.75 20.25l1.5-1.5m0 0l8.25-8.25");
}

.tl4qwzjft {
  d: path("M18 21.5c-1.75-2-3-3.5-3-5a3 3 0 0 1 6 0c0 1.5-1.25 3-3 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
