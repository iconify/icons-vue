<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oebfqqbis"/><path class="d-ir2xbuo"/><path class="b6e35tlvq"/><path class="yvu-_lcqx"/><path class="yjzas4brk"/><path class="w74_pkbuu"/><path class="nj-oiubfo"/><path class="r7xk8o29f"/><path class="sunqexbsa"/><path class="om2raabrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-duotone-bold" /></template>
<style>
.b6e35tlvq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d-ir2xbuo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nj-oiubfo {
  d: path("M8 7v10");
}

.oebfqqbis {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.om2raabrv {
  d: path("M20 10v4");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sunqexbsa {
  d: path("M16 7v10");
}

.w74_pkbuu {
  d: path("M4 10v4");
}

.yjzas4brk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvu-_lcqx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
