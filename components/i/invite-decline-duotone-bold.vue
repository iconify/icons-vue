<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y8z8cuc_n"/><path class="u9zbhwwpi"/><path class="er-rmmbme"/><path class="i-eao3sns"/><path class="b3d1hobxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invite-decline-duotone-bold" /></template>
<style>
.b3d1hobxs {
  d: path("m22 13 -4 4");
}

.er-rmmbme {
  d: path("M6 10V5h6v5");
}

.i-eao3sns {
  d: path("m18 13 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9zbhwwpi {
  d: path("M2 10v9h14v-9Z");
}

.y8z8cuc_n {
  fill: currentColor;
  d: path("M2 10v9h14v-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
