<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nfnuaabzh"/><path class="o-carab-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-duocolor-sharp" /></template>
<style>
.nfnuaabzh {
  stroke-opacity: 0.4;
  d: path("M9.172 4.172A4 4 0 0 1 16 7v2M2 3l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-carab-v {
  d: path("M20 21H4V9h4m6 0h6v6");
}

</style>
