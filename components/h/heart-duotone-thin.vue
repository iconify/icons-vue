<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="khavsabnb"/><path class="v8zf5mxaf"/><path class="xmoymgtle"/><path class="pdm45_o_b"/><path class="w_otj1bev"/><path class="e1uudcbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heart-duotone-thin" /></template>
<style>
.e1uudcbua {
  d: path("m4 9 8 8 8 -8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khavsabnb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pdm45_o_b {
  d: path("M4 9a4 4 0 0 1 8 0");
}

.v8zf5mxaf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w_otj1bev {
  d: path("M12 9a4 4 0 0 1 8 0");
}

.xmoymgtle {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 9 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
