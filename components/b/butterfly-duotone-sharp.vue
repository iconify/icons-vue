<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f_k4yroep"/><path class="lnl-bwbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:butterfly-duotone-sharp" /></template>
<style>
.f_k4yroep {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 8.243c1.206-1.538 2.867-2.982 4.678-3.736C17.413 4.2 18.2 4 19 4a3 3 0 0 1 2.12.88A3 3 0 0 1 22 7c0 .777-.063 1.559-.247 2.315c-.496 2.033-1.784 3.425-3.49 4.546C19.375 14.581 20 15.647 20 17c0 2.248-1.752 4-4 4c-1.381 0-2.941-.221-4-1.192C10.941 20.779 9.381 21 8 21c-2.248 0-4-1.752-4-4c0-1.353.625-2.419 1.737-3.139c-1.706-1.121-2.994-2.513-3.49-4.546C2.063 8.559 2 7.777 2 7a3 3 0 0 1 .88-2.12A3 3 0 0 1 5 4c.8 0 1.587.2 2.322.507c1.811.755 3.472 2.198 4.678 3.736");
}

.ft5dv1b6b {
  fill: none;
}

.lnl-bwbbv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10c1.5-2.5 4.5-5 7-5c1.1 0 2 .9 2 2c0 3-1 5-5 7q3 .75 3 3c0 1.7-1.3 3-3 3c-2 0-3.5-.5-4-2m0-8c-1.5-2.5-4.5-5-7-5c-1.1 0-2 .9-2 2c0 3 1 5 5 7q-3 .75-3 3c0 1.7 1.3 3 3 3c2 0 3.5-.5 4-2m0-11v11");
}

</style>
