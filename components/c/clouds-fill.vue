<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="htpq-ccws"/><path clip-rule="evenodd" class="cht1h3b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clouds-fill" /></template>
<style>
.cht1h3b6h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 21C2.7909 21 1 19.2091 1 17C1 15.1481 2.2712 13.5383 4.0727 13.109C4.509 10.4509 6.8063 8.5 9.5 8.5C12.1937 8.5 14.491 10.4509 14.9273 13.109C16.7288 13.5383 18 15.1481 18 17C18 19.2091 16.2091 21 14 21L5 21Z");
  stroke: none;
}

.htpq-ccws {
  d: path("M18.8989 12L19.5 12C20.8807 12 22 10.8807 22 9.5C22 8.1193 20.8807 7 19.5 7C19.5 5.3431 18.1569 4 16.5 4C15.0285 4 13.7742 5.0673 13.5387 6.5198");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
