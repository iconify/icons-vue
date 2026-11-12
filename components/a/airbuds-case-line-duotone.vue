<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aa0ewkb8e"/><path class="i-vl_3bog"/><path class="ozdm5k_ze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-line-duotone" /></template>
<style>
.aa0ewkb8e {
  d: path("M20.9928 9H17M7.00012 9H3.00732");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i-vl_3bog {
  d: path("M12 22C8.25027 22 6.3754 22 5.06107 21.0451C4.6366 20.7367 4.26331 20.3634 3.95491 19.9389C3 18.6246 3 16.7497 3 13V11C3 7.25027 3 5.3754 3.95491 4.06107C4.26331 3.6366 4.6366 3.26331 5.06107 2.95491C6.3754 2 8.25027 2 12 2C15.7497 2 17.6246 2 18.9389 2.95491C19.3634 3.26331 19.7367 3.6366 20.0451 4.06107C21 5.3754 21 7.25027 21 11V13C21 16.7497 21 18.6246 20.0451 19.9389C19.7367 20.3634 19.3634 20.7367 18.9389 21.0451C17.6246 22 15.7497 22 12 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozdm5k_ze {
  d: path("M9 11H15C16.1046 11 17 10.1046 17 9C17 7.89543 16.1046 7 15 7H9C7.89543 7 7 7.89543 7 9C7 10.1046 7.89543 11 9 11Z");
}

</style>
