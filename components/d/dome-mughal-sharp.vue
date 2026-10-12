<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="znjv3-bjw"/><path class="dbwsrvb9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dome-mughal-sharp" /></template>
<style>
.dbwsrvb9b {
  d: path("M10.5 21.25V18h3v3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znjv3-bjw {
  d: path("M12 2.75V4.5m0 0C13 6 15 7 17 8.75s2.75 3.75 2.25 6.25H4.75C4.25 12.5 5 10.5 7 8.75S11 6 12 4.5ZM5.5 15h13v6.25h-13z");
}

</style>
