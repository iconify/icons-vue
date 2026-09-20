<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_oqy2n_y"/><path class="rtc4d5stj"/><path class="yz3ytyhzk"/><path class="e77gki8ci"/><path class="mvm7r4bea"/><path class="yt5ezyvwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fulfilment-centre-duotone-regular" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_oqy2n_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rtc4d5stj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yt5ezyvwf {
  d: path("M13.5 11.5 16 14l-2.5 2.5");
}

.yz3ytyhzk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 11.5 16 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
