<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y5c7dqbak"/><path class="a4r9jjopi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:compass-duotone-sharp" /></template>
<style>
.a4r9jjopi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m9-5l2 5l-2 5l-2-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.y5c7dqbak {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 21a9 9 0 0 1-9-9a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9m2-9l-2-5l-2 5l2 5Z");
}

</style>
