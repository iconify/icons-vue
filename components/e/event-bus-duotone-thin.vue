<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="px1u_4qiq"/><path class="p24r95ukg"/><path class="sc-gdybyv"/><path class="h3piw-bad"/><path class="x26a8iq1c"/><path class="ugztwkaee"/><path class="j-bg0m85s"/><path class="th8j40bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-bus-duotone-thin" /></template>
<style>
.h3piw-bad {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-bg0m85s {
  d: path("M12 14.5V19");
}

.p24r95ukg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.px1u_4qiq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sc-gdybyv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14.5V19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.th8j40bfn {
  d: path("M18 5v4.5");
}

.ugztwkaee {
  d: path("M6 5v4.5");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

</style>
