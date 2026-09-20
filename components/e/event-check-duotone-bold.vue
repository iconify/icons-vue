<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v6vao-e4h"/><path class="cm7pnfbnp"/><path class="v-jogvb5z"/><path class="l9-vpjbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-check-duotone-bold" /></template>
<style>
.cm7pnfbnp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 14 2.5 2.5L20 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9-vpjbes {
  d: path("m13 14 2.5 2.5L20 12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

.v6vao-e4h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
