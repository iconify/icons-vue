<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l7x-pjmpb"/><path class="m-bkxlbfb"/><path class="w4giizb1e"/><path class="q5bla5t6u"/><path class="v1y9d1bvi"/><path class="e9wqqffiv"/><path class="h26hx985n"/><path class="x8hgqsbhk"/><path class="bzfuiwbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:adhesive-plaster-linear" /></template>
<style>
.bzfuiwbgo {
  stroke-linejoin: round;
  d: path("M8.75 8.75H8.7501");
}

.e9wqqffiv {
  stroke-linejoin: round;
  d: path("M15.2969 13.4204H15.297");
}

.h26hx985n {
  stroke-linejoin: round;
  d: path("M13.4297 15.2798H13.4298");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7x-pjmpb {
  d: path("M20.7868 20.7868C19.1692 22.4044 16.5465 22.4044 14.9289 20.7868L3.2132 9.07107C1.5956 7.45346 1.5956 4.83081 3.2132 3.2132C4.83081 1.5956 7.45346 1.5956 9.07107 3.2132L20.7868 14.9289C22.4044 16.5465 22.4044 19.1692 20.7868 20.7868Z");
}

.m-bkxlbfb {
  d: path("M9.07107 20.7868L12 17.8579L6.14214 12L3.2132 14.9289C1.5956 16.5465 1.5956 19.1692 3.2132 20.7868C4.83081 22.4044 7.45346 22.4044 9.07107 20.7868ZM14.9289 3.2132L12 6.14214L17.8579 12L20.7868 9.07107C22.4044 7.45346 22.4044 4.83081 20.7868 3.2132C19.1692 1.5956 16.5465 1.5956 14.9289 3.2132Z");
}

.q5bla5t6u {
  stroke-linejoin: round;
  d: path("M9.7168 11.5688H9.7169");
}

.v1y9d1bvi {
  stroke-linejoin: round;
  d: path("M12.5 12.5H12.5001");
}

.w4giizb1e {
  stroke-linejoin: round;
  d: path("M11.5732 9.71191H11.5733");
}

.x8hgqsbhk {
  stroke-linejoin: round;
  d: path("M16.2158 16.2026H16.2159");
}

</style>
