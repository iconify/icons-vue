<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n1hkonb1z"/><path class="btfehzbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keffiyeh-sharp" /></template>
<style>
.btfehzbmn {
  d: path("M9.5 11c0 2.5 1 4.25 2.5 4.25s2.5-1.75 2.5-4.25M5.75 8.25c4-1.75 8.5-1.75 12.5 0M6.25 18v3.25m3-3.25v3.25m5.5-3.25v3.25m3-3.25v3.25");
}

.n1hkonb1z {
  d: path("M12 3c-4.75 0-7 3-7 7.5L2.75 21.25h18.5L19 10.5C19 6 16.75 3 12 3Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
