<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dnmgxtb7v"/><path class="jycpvgb1i"/><path class="qpuuxkb2r"/><path class="cfwhgr43a"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:emergency-room-duotone-bold" /></template>
<style>
.cfwhgr43a {
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
}

.dnmgxtb7v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jycpvgb1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qpuuxkb2r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
