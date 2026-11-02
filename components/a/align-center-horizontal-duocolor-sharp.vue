<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="now253bdc"/><path class="lbtgvnapo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-horizontal-duocolor-sharp" /></template>
<style>
.lbtgvnapo {
  d: path("M4 4h16v6H4Zm2 10h12v6H6Z");
}

.now253bdc {
  stroke-opacity: 0.4;
  d: path("M12 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
