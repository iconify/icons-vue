<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nuuzvbbgc"/><path class="wvltndbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuuzvbbgc {
  fill: currentColor;
  d: path("M1 5C1 3.8954 1.8954 3 3 3L7 3C8.1046 3 9 3.8954 9 5L9 9C9 10.1046 8.1046 11 7 11L3 11C1.8954 11 1 10.1046 1 9L1 5Z");
  stroke: none;
}

.wvltndbcs {
  d: path("M12 7L22 7M12 18L22 18M2 18L4 20L8 16");
}

</style>
