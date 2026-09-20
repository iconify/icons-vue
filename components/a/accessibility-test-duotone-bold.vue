<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_vo3wz-j"/><path class="yeoa2yx7i"/><path class="czoh5nbjc"/><path class="i36zaq-hn"/><path class="fozhwebbv"/><path class="tl_0od7zv"/><path class="ysxlqwpgz"/><path class="aaofdybgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessibility-test-duotone-bold" /></template>
<style>
.aaofdybgo {
  d: path("m9 18 3 -3 3 3");
}

.czoh5nbjc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fozhwebbv {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.i36zaq-hn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 18 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_vo3wz-j {
  fill: currentColor;
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.tl_0od7zv {
  d: path("M6 10.5h12");
}

.yeoa2yx7i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10.5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ysxlqwpgz {
  d: path("M12 10.5V15");
}

</style>
