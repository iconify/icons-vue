<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vz9hcp7lr"/><path class="c7uwtubfk"/><path class="yvg88mbgu"/><path class="zkx1g3b3t"/><path class="ghpezkxlh"/><path class="v3xsaib0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-cup-duotone-thin" /></template>
<style>
.c7uwtubfk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghpezkxlh {
  d: path("M15 7a3 3 0 0 1 0 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3xsaib0o {
  d: path("M2 19h15");
}

.vz9hcp7lr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7v9h11V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvg88mbgu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zkx1g3b3t {
  d: path("M4 7v9h11V7");
}

</style>
