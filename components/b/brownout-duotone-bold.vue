<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jhciu1yca"/><path class="hsmhdqayv"/><path class="hb5bs7bvv"/><path class="kdybz_aht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:brownout-duotone-bold" /></template>
<style>
.hb5bs7bvv {
  d: path("M13 3 8 8h3.5l-5 5");
}

.hsmhdqayv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jhciu1yca {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 3 8 8h3.5l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kdybz_aht {
  d: path("M9 17h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
