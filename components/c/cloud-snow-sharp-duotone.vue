<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dbp_a1trw"/><path class="m52hd4boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-snow-sharp-duotone" /></template>
<style>
.dbp_a1trw {
  stroke-opacity: 0.4;
  d: path("M5.751 17.067L5 16.874C3.275 16.43 2 14.864 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 14.864 20.725 16.43 19 16.874L18.249 17.067");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m52hd4boy {
  d: path("M12 13V17.5M12 17.5V22M12 17.5L8.504 15.461M12 17.5L15.496 19.539M12 17.5L8.504 19.539M12 17.5L15.496 15.461");
}

</style>
