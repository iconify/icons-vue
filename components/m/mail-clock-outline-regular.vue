<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vizlgibdt"/><path class="im9sid5gw"/><path class="r9il7jbjw"/><path class="b2n99wbku"/><path class="q829csbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-clock-outline-regular" /></template>
<style>
.b2n99wbku {
  d: path("M12 12.5v3");
}

.im9sid5gw {
  d: path("m5 9.5 7 -7 7 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q829csbzu {
  d: path("M12 15.5h2.5");
}

.r9il7jbjw {
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vizlgibdt {
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
