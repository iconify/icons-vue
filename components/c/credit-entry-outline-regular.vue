<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="okqksmbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-entry-outline-regular" /></template>
<style>
.bg2ejdbaq {
  d: path("M12 5v16");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okqksmbze {
  d: path("M14.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
