<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="fti-unbge"/><path class="ry7zsib4b"/><path class="c8crs_1ho"/><path class="pd4wpfbua"/><path class="ymw3aibdo"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="cm0vclbrz"/><path class="j66gzwnbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-tree-duotone-regular" /></template>
<style>
.aq5i5tblx {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.c8crs_1ho {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v4H6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cm0vclbrz {
  d: path("M12 7v4H6v4");
}

.fti-unbge {
  fill: currentColor;
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j66gzwnbv {
  d: path("M12 11h6v4");
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.p83l94bht {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pd4wpfbua {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11h6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ry7zsib4b {
  fill: currentColor;
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
