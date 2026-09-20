<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x26a8iq1c"/><path class="ugztwkaee"/><path class="j-bg0m85s"/><path class="th8j40bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-bus-outline-regular" /></template>
<style>
.j-bg0m85s {
  d: path("M12 14.5V19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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
