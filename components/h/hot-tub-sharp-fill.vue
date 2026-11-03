<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dr3v0jbck"/><path class="rq66s6r2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hot-tub-sharp-fill" /></template>
<style>
.dr3v0jbck {
  fill: currentColor;
  d: path("M22 12.0001L22 19C22 19.5523 21.5523 20 21 20L3 20C2.4477 20 2 19.5523 2 19L2 12.0001L1 12.0001L1 10.0001L2.988 10.0001C2.992 10 2.996 10 3 10L21 10C21.004 10 21.008 10 21.012 10.0001L23 10.0001L23 12.0001L22 12.0001Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rq66s6r2e {
  d: path("M3 11L3 3L6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.2071 5.7929L10.2929 2.7071M8 19L6.7236 21.5528M16 19L17.2764 21.5528M15 2L15 3.1972C15 4.3727 14.6521 5.5219 14 6.5C13.8919 6.6622 13.7921 6.8291 13.7009 7L13.2301 7.8822M20 2L20 3.1972C20 4.3727 19.6521 5.5219 19 6.5C18.8919 6.6622 18.7921 6.8291 18.7009 7L18.2301 7.8822");
}

</style>
