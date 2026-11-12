<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oaddbsbpv"/><path class="p-hr47b7d"/><path class="tzwo1sgpu"/><path class="iezy05bsl"/><path class="slcm6pbxr"/><path class="pb8r5z_os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checklist-broken" /></template>
<style>
.iezy05bsl {
  d: path("M22 12H17M13.5 12H12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oaddbsbpv {
  stroke-linejoin: round;
  d: path("M2 5.5L3.21429 7L7.5 3");
}

.p-hr47b7d {
  stroke-linejoin: round;
  d: path("M2 12.5L3.21429 14L7.5 10");
}

.pb8r5z_os {
  d: path("M22 5L12 5");
}

.slcm6pbxr {
  d: path("M12 19H17M20.5 19H22");
}

.tzwo1sgpu {
  stroke-linejoin: round;
  d: path("M2 19.5L3.21429 21L7.5 17");
}

</style>
