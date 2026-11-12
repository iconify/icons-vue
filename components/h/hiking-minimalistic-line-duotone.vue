<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="einr_36wa"/><path class="joe83l06m"/><path class="a9p1k1bev"/><path class="aji3_8bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-minimalistic-line-duotone" /></template>
<style>
.a9p1k1bev {
  stroke-linejoin: round;
  d: path("M18.999 9.5L18.5757 9.85275C17.0104 11.1571 14.8214 11.4112 12.999 10.5C11.8366 9.80255 10.3438 10.5521 10.2089 11.901L10.1403 12.5871C10.0538 13.4523 10.4657 14.2917 11.2031 14.7526L11.5364 14.9609C13.0874 15.9303 14.0943 17.5707 14.2564 19.3926L14.3994 21");
}

.aji3_8bki {
  d: path("M19 21V7");
}

.einr_36wa {
  cx: 11.5px;
  cy: 5.5px;
  r: 2.5px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.joe83l06m {
  d: path("M9 16.5C9 16.5 8.57441 18.1192 8 19C7.39661 19.9252 6 21 6 21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
