<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lsc1gmb0c"/><path class="yj9kk6wvp"/><path class="jm8csxnlh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferret-sharp" /></template>
<style>
.jm8csxnlh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.5h.01");
}

.lsc1gmb0c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5v-.767l.75-.333l3-1.4l1.125-.75h9.125c2 0 3.5 1.4 3.5 3.25v1.875l-1.75.875v2.25h-2.25v-2.25H10.5v2.25H8.25V15l-1.125-.375l-.875-.875l-2.75-.15l-.75-.167z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yj9kk6wvp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20 14l1.25 2.083V19M7.75 9.6L7.5 7.75");
}

</style>
