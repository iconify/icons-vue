<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ld-zqchrg"/><path class="rt55a5byn"/><path class="l9ptwpbxd"/><path class="k-9q2cbvs"/><path class="ju4i6gx3w"/><path class="dtjohzbue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fold-clothes-duotone-bold" /></template>
<style>
.dtjohzbue {
  d: path("M5 17h14v3H5Z");
}

.ju4i6gx3w {
  d: path("M7 11h10v3H7Z");
}

.k-9q2cbvs {
  d: path("M5 5h14v3H5Z");
}

.l9ptwpbxd {
  fill: currentColor;
  d: path("M5 17h14v3H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ld-zqchrg {
  fill: currentColor;
  d: path("M5 5h14v3H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rt55a5byn {
  fill: currentColor;
  d: path("M7 11h10v3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
