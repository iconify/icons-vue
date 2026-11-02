<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ou8j9pw5a"/><path class="j7p7fjlcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-duocolor-sharp" /></template>
<style>
.j7p7fjlcb {
  d: path("M9 6h6v12H9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ou8j9pw5a {
  stroke-opacity: 0.4;
  d: path("M4 3v18M20 3v18");
}

</style>
