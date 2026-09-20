<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rxwr8htky"/><path class="mti18-d5p"/><path class="jcwhwvnse"/><path class="l3ca9u8kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:consumer-duotone-bold" /></template>
<style>
.jcwhwvnse {
  d: path("M12.24 16.24a6 6 0 1 1 0 -8.5");
}

.l3ca9u8kt {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mti18-d5p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.24 16.24a6 6 0 1 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rxwr8htky {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

</style>
