<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r1oykbb0j"/><path class="yi0_aveoy"/><path class="krbf_7blk"/><path class="mcj52c2nx"/><path class="hwkcvpp-j"/><path class="ihfql7bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:epoch-duotone-bold" /></template>
<style>
.hwkcvpp-j {
  d: path("M12 6a6 6 0 1 1 -6 6");
}

.ihfql7bsw {
  d: path("M12 9a3 3 0 1 1 -3 3");
}

.krbf_7blk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcj52c2nx {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

.r1oykbb0j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3a9 9 0 1 1 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yi0_aveoy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6a6 6 0 1 1 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
