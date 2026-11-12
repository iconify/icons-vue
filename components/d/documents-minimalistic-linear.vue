<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b-bymobfb"/><path class="jj9sgub3y"/><path class="sn70fibvm"/><path class="rldmr4bdt"/><path class="dkgqo5bmm"/><path class="pa1nt9q2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-minimalistic-linear" /></template>
<style>
.b-bymobfb {
  d: path("M11 22H13C15.8284 22 17.2426 22 18.1213 21.1213C19 20.2426 19 18.8284 19 16V8C19 5.17157 19 3.75736 18.1213 2.87868C17.2426 2 15.8284 2 13 2H11C8.17157 2 6.75736 2 5.87868 2.87868C5 3.75736 5 5.17157 5 8V16C5 18.8284 5 20.2426 5.87868 21.1213C6.75736 22 8.17157 22 11 22Z");
}

.dkgqo5bmm {
  d: path("M2 19V5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj9sgub3y {
  d: path("M9 13H15");
}

.pa1nt9q2d {
  d: path("M22 19V5");
}

.rldmr4bdt {
  d: path("M9 17H12");
}

.sn70fibvm {
  d: path("M9 9H15");
}

</style>
