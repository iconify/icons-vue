<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="ox5l_oflw"/><path class="mojmrdb8z"/><path class="xgrfb-bqu"/><path class="x22av82oi"/><path class="cn-9z7b7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-left-duotone-regular" /></template>
<style>
.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cn-9z7b7f {
  d: path("M3 18h15");
}

.mojmrdb8z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox5l_oflw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x22av82oi {
  d: path("M3 12h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
