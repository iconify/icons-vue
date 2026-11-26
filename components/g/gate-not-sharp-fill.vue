<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="i8slu90vt"/><path class="m9d5xj3pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-not-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i8slu90vt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.9789 8.1221L18.4789 11.1221C18.8001 11.2973 19 11.6341 19 12C19 12.3659 18.8001 12.7027 18.4789 12.8779L7.4789 18.8779C7.332 18.958 7.1673 19 7 19C6.4477 19 6 18.5523 6 18L6 6C6 5.4477 6.4477 5 7 5C7.1673 5 7.332 5.042 7.4789 5.1221Z");
  stroke: none;
}

.m9d5xj3pc {
  d: path("M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12C22 13.1046 21.1046 14 20 14C18.8954 14 18 13.1046 18 12ZM1 12L7 12");
}

</style>
