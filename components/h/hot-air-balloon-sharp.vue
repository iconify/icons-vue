<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lkd3mjb3f"/><path class="i85_nkb6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-air-balloon-sharp" /></template>
<style>
.i85_nkb6b {
  d: path("M10 15.75C8.25 13 8 7 12 3m2 12.75C15.75 13 16 7 12 3M9.75 15.75l.5 3m4-3l-.5 3m-4 0h4.5v2.5h-4.5z");
}

.lkd3mjb3f {
  d: path("M12 2.75A7.25 7.25 0 0 0 4.75 10c0 2.6 2 4.5 4.5 5.75h5.5c2.5-1.25 4.5-3.15 4.5-5.75A7.25 7.25 0 0 0 12 2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
