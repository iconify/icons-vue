<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="q6_4crz9y"/><path class="y_9sttbia"/><path class="skbifdbcx"/><path class="qn5d-0b_j"/><path class="jkpgw6k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-context-duotone-bold" /></template>
<style>
.jkpgw6k5z {
  d: path("M19.5 12H22v9h-2.5");
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6_4crz9y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 12H12v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qn5d-0b_j {
  d: path("M14.5 12H12v9h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.y_9sttbia {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.5 12H22v9h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
