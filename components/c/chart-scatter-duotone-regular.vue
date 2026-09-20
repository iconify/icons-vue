<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mk0cvynsk"/><path class="vfk9p6bsw"/><path class="ky48x0b1z"/><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="ynh89jb5g"/><path class="cg4ywvb4m"/><path class="a6m5kfb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-scatter-duotone-regular" /></template>
<style>
.a6m5kfb7k {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.cg4ywvb4m {
  d: path("M12 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky48x0b1z {
  fill: currentColor;
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mk0cvynsk {
  fill: currentColor;
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.vfk9p6bsw {
  fill: currentColor;
  d: path("M12 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ynh89jb5g {
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
