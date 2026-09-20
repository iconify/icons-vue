<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ftq_9nbqu"/><path class="mmx7g9jzy"/><path class="it88l1wbh"/><path class="w_jkatblo"/><path class="qg37n0byb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:film-roll-duotone-regular" /></template>
<style>
.ftq_9nbqu {
  fill: currentColor;
  d: path("M3 7v10h18V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.it88l1wbh {
  d: path("M7 7v10");
}

.mmx7g9jzy {
  d: path("M3 7v10h18V7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qg37n0byb {
  d: path("M17 7v10");
}

.w_jkatblo {
  d: path("M12 7v10");
}

</style>
