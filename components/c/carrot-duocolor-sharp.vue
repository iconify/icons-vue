<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f77qxutat"/><path class="f1xa8sbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:carrot-duocolor-sharp" /></template>
<style>
.f1xa8sbih {
  d: path("M3 21L9 9c1.343-2.687 4.958-3.203 7-1c2.203 2.042 1.687 5.657-1 7Zm5-10l2 1m1 5l-2-1");
}

.f77qxutat {
  stroke-opacity: 0.4;
  d: path("M16 3c-1.948.625-2.125 2.917 0 5c2.125-2.083 1.948-4.375 0-5m5 5c-.625 1.948-2.917 2.125-5 0c2.083-2.125 4.375-1.948 5 0m-5 0h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
