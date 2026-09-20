<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqwo1bbye"/><path class="guuk32q1o"/><path class="v-jogvb5z"/><path class="racsvxx3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-spike-duotone-regular" /></template>
<style>
.guuk32q1o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 18h3l3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.racsvxx3t {
  d: path("M12 18h3l3 -3 3 3");
}

.sqwo1bbye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
