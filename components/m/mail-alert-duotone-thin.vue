<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="adpm_c_dx"/><path class="nvygi8bzm"/><path class="vizlgibdt"/><path class="im9sid5gw"/><path class="b2n99wbku"/><path class="uy7nmfbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-alert-duotone-thin" /></template>
<style>
.adpm_c_dx {
  fill: currentColor;
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.b2n99wbku {
  d: path("M12 12.5v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.im9sid5gw {
  d: path("m5 9.5 7 -7 7 7");
}

.nvygi8bzm {
  fill: currentColor;
  d: path("M11 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uy7nmfbhi {
  d: path("M11 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vizlgibdt {
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
