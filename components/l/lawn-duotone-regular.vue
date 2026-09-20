<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dk2_9r6pl"/><path class="rfbiofnyk"/><path class="qerooxbvn"/><path class="fa1rvigpb"/><path class="o8od38cnm"/><path class="tktvzqb2t"/><path class="f__nic5ty"/><path class="mcne0zbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lawn-duotone-regular" /></template>
<style>
.dk2_9r6pl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f__nic5ty {
  d: path("M12 18V6");
}

.fa1rvigpb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 18c0 -4 1 -7 2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcne0zbsf {
  d: path("M17 18c0 -4 1 -7 2 -11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.qerooxbvn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 18V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfbiofnyk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 18c0 -4 -1 -7 -2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tktvzqb2t {
  d: path("M7 18c0 -4 -1 -7 -2 -11");
}

</style>
