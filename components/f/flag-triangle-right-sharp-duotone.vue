<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="urpfq9swt"/><path class="kym307rds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-triangle-right-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kym307rds {
  stroke-opacity: 0.4;
  d: path("M4 1L4 23");
}

.urpfq9swt {
  fill: currentColor;
  d: path("M4.3511 3.0637L20.3511 9.0637C20.7414 9.21 21 9.5832 21 10C21 10.4168 20.7414 10.79 20.3511 10.9363L4.3511 16.9363C4.2388 16.9784 4.1199 17 4 17C3.4477 17 3 16.5523 3 16L3 4C3 3.4477 3.4477 3 4 3C4.1199 3 4.2388 3.0216 4.3511 3.0637Z");
  stroke: none;
}

</style>
