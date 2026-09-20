<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sg5tbcboo"/><path class="fzx2-xbbx"/><path class="vi0rmgvkt"/><path class="d5ewpzb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leaf-fall-duotone-bold" /></template>
<style>
.d5ewpzb2a {
  d: path("M12 20c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

.fzx2-xbbx {
  fill: currentColor;
  d: path("M12 20c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sg5tbcboo {
  fill: currentColor;
  d: path("M4 11c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vi0rmgvkt {
  d: path("M4 11c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

</style>
