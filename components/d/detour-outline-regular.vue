<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vhfgw5-us"/><path class="a-ogebbgz"/><path class="e2evtpg8i"/><path class="q4rhaacat"/><path class="hv2_9fjhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:detour-outline-regular" /></template>
<style>
.a-ogebbgz {
  d: path("M12 7v9");
}

.e2evtpg8i {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

.hv2_9fjhy {
  d: path("m20 13 -4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q4rhaacat {
  d: path("m16 13 4 4");
}

.vhfgw5-us {
  d: path("M2 16h10");
}

</style>
