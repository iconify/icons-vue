<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oaddbsbpv"/><path class="izz72qbqz"/><path class="tzwo1sgpu"/><path class="hrf5bu8dg"/><path class="ccd9x7b2v"/><path class="pb8r5z_os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checklist-line-duotone" /></template>
<style>
.ccd9x7b2v {
  d: path("M22 12L12 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hrf5bu8dg {
  d: path("M22 19L12 19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izz72qbqz {
  stroke-linejoin: round;
  d: path("M2 12.5L3.21429 14L7.5 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.oaddbsbpv {
  stroke-linejoin: round;
  d: path("M2 5.5L3.21429 7L7.5 3");
}

.pb8r5z_os {
  d: path("M22 5L12 5");
}

.tzwo1sgpu {
  stroke-linejoin: round;
  d: path("M2 19.5L3.21429 21L7.5 17");
}

</style>
