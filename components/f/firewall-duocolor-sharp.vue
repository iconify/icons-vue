<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w48f3uc3t"/><path class="zxdqc-b5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewall-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w48f3uc3t {
  stroke-opacity: 0.4;
  d: path("M12 3c.25 1.25 1 2.25 2 3c.75.75 1 1.75 1 3a3 3 0 1 1-6 0c0-.75.25-1.25.5-1.5m0 0a1 1 0 1 0 2 0c0-.75-.25-1-.5-1.5c-.5-1-.25-2 1-3");
}

.zxdqc-b5m {
  d: path("M3 15h18v6H3Zm0 3h18M9 15v3m6 0v3");
}

</style>
