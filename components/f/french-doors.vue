<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nf-yq7b_r"/><path class="k0gcmjjab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:french-doors" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0gcmjjab {
  d: path("M7.75 5.5H8A1.5 1.5 0 0 1 9.5 7v3A1.5 1.5 0 0 1 8 11.5h-.25a1.5 1.5 0 0 1-1.5-1.5V7a1.5 1.5 0 0 1 1.5-1.5m8.25 0h.25a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H16a1.5 1.5 0 0 1-1.5-1.5V7A1.5 1.5 0 0 1 16 5.5M10.5 15h.01m2.99 0h.01");
}

.nf-yq7b_r {
  d: path("M6.625 3h10.75A2.625 2.625 0 0 1 20 5.625v12.75A2.625 2.625 0 0 1 17.375 21H6.625A2.625 2.625 0 0 1 4 18.375V5.625A2.625 2.625 0 0 1 6.625 3M12 3v18");
}

</style>
