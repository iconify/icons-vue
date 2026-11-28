<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="ia5g-5b6x"/><path class="n0i5osbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ia5g-5b6x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 12L19 12C19.5523 12 20 12.4477 20 13L20 16C20 16.5523 19.5523 17 19 17L12 17L5 17C4.4477 17 4 16.5523 4 16L4 13C4 12.4477 4.4477 12 5 12ZM8.5 10L5 10C4.4477 10 4 9.5523 4 9L4 2C4 1.4477 4.4477 1 5 1L12 1L19 1C19.5523 1 20 1.4477 20 2L20 9C20 9.5523 19.5523 10 19 10L12 10ZM13.5 6.5C13.5 5.6716 12.8284 5 12 5C11.1716 5 10.5 5.6716 10.5 6.5C10.5 7.3284 11.1716 8 12 8C12.8284 8 13.5 7.3284 13.5 6.5Z");
  stroke: none;
}

.n0i5osbqm {
  d: path("M12 16L12 22L6 22");
}

</style>
