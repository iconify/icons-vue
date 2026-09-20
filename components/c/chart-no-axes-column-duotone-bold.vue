<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iia2w9b1i"/><path class="ncqq4rbxm"/><path class="ydal5-bkx"/><path class="u66cvxjqz"/><path class="h-el3xdlg"/><path class="e9_u-df3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-no-axes-column-duotone-bold" /></template>
<style>
.e9_u-df3m {
  d: path("M18 13v7");
}

.h-el3xdlg {
  d: path("M12 6v14");
}

.iia2w9b1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ncqq4rbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u66cvxjqz {
  d: path("M6 10v10");
}

.ydal5-bkx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
