<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="de9ia5bqk"/><path class="skbifdbcx"/><path class="d0vyaobih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-sleep-duotone-bold" /></template>
<style>
.d0vyaobih {
  d: path("M13 12h8l-8 8h8");
}

.de9ia5bqk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h8l-8 8h8");
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

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
