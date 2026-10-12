<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hm5jbgbsa"/><path class="etc29tg0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lift-shaft-sharp" /></template>
<style>
.etc29tg0w {
  d: path("M8.25 13.75L9.5 12.5l1.25 1.25m2.5-1.25l1.25 1.25l1.25-1.25");
}

.hm5jbgbsa {
  d: path("M2.75 2.75h18.5m-17 0v18.5m15.5-18.5v18.5m-17 0h18.5M12 2.75V7.5m-5 .75h10v9.5H7zm5 1.5v6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
