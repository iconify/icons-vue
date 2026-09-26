<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ww78ztu8g"/><path class="srbob_bob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-left-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.srbob_bob {
  d: path("M2.7693 12L12.8907 12M7.83 6.5L2.1641 11.6314C1.9453 11.8296 1.9453 12.1704 2.1641 12.3686L7.83 17.5");
}

.ww78ztu8g {
  stroke-opacity: 0.4;
  d: path("M12.8907 4L18 4C20.2091 4 22 5.7909 22 8L22 16C22 18.2091 20.2091 20 18 20L12.8907 20");
}

</style>
