<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ibthacczf"/><path class="dm_hjfeqr"/><path class="njnsi8bel"/><path class="nz19jcivh"/><path class="ov7kkt0lo"/><path class="vxy4ztabh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:earthquake-duotone-bold" /></template>
<style>
.dm_hjfeqr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 17 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ibthacczf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 10h4l3 -3 3 3 3 -3 3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.njnsi8bel {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nz19jcivh {
  d: path("M2 10h4l3 -3 3 3 3 -3 3 3h4");
}

.ov7kkt0lo {
  d: path("m8 17 4 4 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vxy4ztabh {
  d: path("M4 14h16");
}

</style>
