<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bjlavremi"/><path class="rbwrj-biq"/><path class="tmlbp1xst"/><path class="ckrzk6zny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cloud-backup-duotone-bold" /></template>
<style>
.bjlavremi {
  fill: currentColor;
  d: path("M4 18a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 9a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ckrzk6zny {
  d: path("M10.5 10.5 8 13l2.5 2.5");
}

.rbwrj-biq {
  d: path("M4 18a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 9a5.5 5.5 0 0 1 4.5 9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tmlbp1xst {
  d: path("M8 13h7");
}

</style>
