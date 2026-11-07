<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kryytllqq"/><path class="kp3dedlav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-warning-duocolor-round" /></template>
<style>
.kp3dedlav {
  d: path("M12 17H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4z");
}

.kryytllqq {
  stroke-opacity: 0.4;
  d: path("M12 7v3m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
