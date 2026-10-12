<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ykk3_-bpd"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baseball-diamond" /></template>
<style>
.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ykk3_-bpd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 6.25l4 4m0 3.5l-4 4m-3.5 0l-4-4m0-3.5l4-4m2.03-2.97l.94.94q.28.28 0 .56l-.94.94q-.28.28-.56 0l-.94-.94q-.28-.28 0-.56l.94-.94q.28-.28.56 0m7.5 7.5l.94.94q.28.28 0 .56l-.94.94q-.28.28-.56 0l-.94-.94q-.28-.28 0-.56l.94-.94q.28-.28.56 0m-15 0l.94.94q.28.28 0 .56l-.94.94q-.28.28-.56 0l-.94-.94q-.28-.28 0-.56l.94-.94q.28-.28.56 0m7.55 7.95l1.09.79q.33.23.33.63v.7q0 .4-.4.4h-2.7q-.4 0-.4-.4v-.7q0-.4.33-.63l1.09-.79q.33-.23.66 0");
}

</style>
