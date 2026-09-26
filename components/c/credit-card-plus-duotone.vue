<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyd-8pbto"/><path class="h4ecpzjaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-plus-duotone" /></template>
<style>
.h4ecpzjaq {
  d: path("M4 9L20 9M19 14L19 20M16 17L22 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vyd-8pbto {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L19 3C21.2091 3 23 4.7909 23 7L23 10C23 10.5523 22.5523 11 22 11L16 11C14.3431 11 13 12.3431 13 14L13 20C13 20.5523 12.5523 21 12 21L5 21C2.7909 21 1 19.2091 1 17L1 7C1 4.7909 2.7909 3 5 3Z");
  stroke: none;
}

</style>
