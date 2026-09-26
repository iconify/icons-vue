<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lqs4ef90h"/><path class="bpjp17mqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-box-sharp-duotone" /></template>
<style>
.bpjp17mqm {
  stroke-opacity: 0.4;
  d: path("M15 3L19 3M21 5L21 9M19 11L15 11M13 5L13 9");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lqs4ef90h {
  d: path("M6 14L6 3M9.2929 6.2929L6 3L2.7071 6.2929M10 18L21 18M17.7071 21.2929L21 18L17.7071 14.7071");
}

</style>
