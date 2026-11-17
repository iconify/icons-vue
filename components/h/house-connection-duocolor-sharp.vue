<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="klsy0lb8n"/><path class="wxmc1yhhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-duocolor-sharp" /></template>
<style>
.klsy0lb8n {
  stroke-opacity: 0.4;
  d: path("M12 17v4m-8 0h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wxmc1yhhu {
  d: path("m12 3l6.222 5.444V17H5.778V8.444z");
}

</style>
