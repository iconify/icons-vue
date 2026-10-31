<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nbxk-cbgb"/><path class="kec7ed3hl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kec7ed3hl {
  d: path("M12 2L12 7M8 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4L18.2929 4.2929");
}

.nbxk-cbgb {
  fill: currentColor;
  d: path("M16 10L18 10C18.5523 10 19 10.4477 19 11L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 11C5 10.4477 5.4477 10 6 10L8 10L8 7C8 6.4477 8.4477 6 9 6L15 6C15.5523 6 16 6.4477 16 7L16 10Z");
  stroke: none;
}

</style>
