<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="hoff7529r"/><path class="e5ok118ga"/><path class="skbifdbcx"/><path class="zj4mz4frt"/><path class="shm5lmr1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-merge-duotone-bold" /></template>
<style>
.e5ok118ga {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 15 -4 -4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hoff7529r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 11v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.shm5lmr1k {
  d: path("m21 15 -4 -4h-4");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.zj4mz4frt {
  d: path("M21 11v10");
}

</style>
