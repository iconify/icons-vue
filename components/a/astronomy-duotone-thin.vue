<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dstagacts"/><path class="arox4o3qw"/><path class="ik6mh31gy"/><path class="gv5aqrbwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:astronomy-duotone-thin" /></template>
<style>
.arox4o3qw {
  d: path("m5 12 8 -8 4 4 -8 8Z");
}

.dstagacts {
  fill: currentColor;
  d: path("m5 12 8 -8 4 4 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gv5aqrbwu {
  d: path("M7 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik6mh31gy {
  d: path("M11 14v7");
}

</style>
