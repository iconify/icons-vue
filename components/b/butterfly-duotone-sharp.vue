<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="js8gc-bao"/><path class="lnl-bwbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:butterfly-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.js8gc-bao {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 10c1.5-2.5 4.5-5 7-5c1.1 0 1.994.9 2 2c0 3-1 5-5 7c1.559.39 2.999 1.205 3 3c-.001 1.697-1.303 2.999-3 3c-1.571 0-3.43-.293-4-2c-.57 1.707-2.429 2-4 2c-1.697-.001-2.999-1.303-3-3c.001-1.795 1.441-2.61 3-3c-4-2-5-4-5-7c0-1.1.9-1.994 2-2c2.5 0 5.5 2.5 7 5");
}

.lnl-bwbbv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10c1.5-2.5 4.5-5 7-5c1.1 0 2 .9 2 2c0 3-1 5-5 7q3 .75 3 3c0 1.7-1.3 3-3 3c-2 0-3.5-.5-4-2m0-8c-1.5-2.5-4.5-5-7-5c-1.1 0-2 .9-2 2c0 3 1 5 5 7q-3 .75-3 3c0 1.7 1.3 3 3 3c2 0 3.5-.5 4-2m0-11v11");
}

</style>
