<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wipgr75ah"/><path class="ujptxiz3v"/><path class="dykyzybzd"/><path class="rrkvivbbw"/><path class="psy6bjy8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-linear" /></template>
<style>
.dykyzybzd {
  d: path("M10 12L14 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.psy6bjy8h {
  d: path("M2 12L6 12");
}

.rrkvivbbw {
  d: path("M18 12L22 12");
}

.ujptxiz3v {
  d: path("M18.1136 22L5.88641 22C4.18426 22 3.33319 22 3.05405 21.4576C2.77491 20.9152 3.26959 20.2226 4.25894 18.8375L5.3884 17.2563C5.8283 16.6404 6.04824 16.3325 6.3713 16.1662C6.69435 16 7.07276 16 7.8296 16L16.1705 16C16.9273 16 17.3057 16 17.6288 16.1662C17.9518 16.3325 18.1718 16.6404 18.6117 17.2563L19.7411 18.8375C20.7305 20.2226 21.2251 20.9152 20.946 21.4576C20.6669 22 19.8158 22 18.1136 22Z");
}

.wipgr75ah {
  d: path("M18.1137 2L5.88641 2C4.18426 2 3.33319 2 3.05405 2.54242C2.77491 3.08484 3.26959 3.77738 4.25894 5.16248L5.3884 6.74372C5.82829 7.35957 6.04824 7.6675 6.3713 7.83375C6.69435 8 7.07276 8 7.8296 8L16.1705 8C16.9273 8 17.3057 8 17.6288 7.83375C17.9518 7.6675 18.1718 7.35957 18.6117 6.74372L19.7411 5.16247C20.7305 3.77738 21.2251 3.08484 20.946 2.54242C20.6669 2 19.8158 2 18.1137 2Z");
}

</style>
