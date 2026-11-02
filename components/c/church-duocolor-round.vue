<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ohdwadw8m"/><path class="vrmgln8ck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohdwadw8m {
  stroke-opacity: 0.4;
  d: path("M12 3v4m-2-2h4");
}

.vrmgln8ck {
  d: path("M8 21v-9c0-.64.36-1.36 1-2l3-3l3 3c.64.64 1 1.36 1 2v9m-8-8l-2 1c-1.226.613-2 1.387-2 2v2a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-2c0-.613-.774-1.387-2-2l-2-1");
}

</style>
