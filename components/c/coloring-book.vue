<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wn3w5rbpl"/><path class="d09xh5buj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coloring-book" /></template>
<style>
.d09xh5buj {
  d: path("M16.75 8a2 2 0 1 1 0 4a2 2 0 1 1 0-4m-3 7c.85-.85 1.65-.85 2.5 0s1.65.85 2.5 0M5 10.25h4M5 13.5h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn3w5rbpl {
  d: path("M12 6.5c-2-1.5-5-2-9.25-1.75v13.5C7 18 10 18.5 12 20c2-1.5 5-2 9.25-1.75V4.75C17 4.5 14 5 12 6.5m0 0v13");
}

</style>
