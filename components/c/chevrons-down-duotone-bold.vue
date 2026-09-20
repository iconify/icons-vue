<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bk1nk6tdv"/><path class="cel7cbwvt"/><path class="kw9oa7xce"/><path class="cdily2n9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-down-duotone-bold" /></template>
<style>
.bk1nk6tdv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 4 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cdily2n9h {
  d: path("m4 13 8 8 8 -8");
}

.cel7cbwvt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 13 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kw9oa7xce {
  d: path("m4 4 8 8 8 -8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
