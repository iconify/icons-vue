<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="xpcq1mbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-duocolor-sharp" /></template>
<style>
.lmxlbqbeq {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xpcq1mbck {
  d: path("M12 17H7l-4 4V2m7 1h11v11m-3 3h-6");
}

</style>
