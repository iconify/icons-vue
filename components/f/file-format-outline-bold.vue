<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tks4a4biu"/><path class="i-xxtdbfm"/><path class="r-3ib9fxz"/><path class="hcn7bdzwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:file-format-outline-bold" /></template>
<style>
.hcn7bdzwu {
  d: path("M15 11v7");
}

.i-xxtdbfm {
  d: path("M9 11v7");
}

.r-3ib9fxz {
  d: path("M12 11v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tks4a4biu {
  d: path("M13 3H6v18h12V8Z");
}

</style>
