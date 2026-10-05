<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow154wb2c"/><path clip-rule="evenodd" class="dm6y1mq_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:homes-duotone" /></template>
<style>
.dm6y1mq_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.0605 7.71096C13.1795 6.76301 14.8205 6.76301 15.9395 7.71096L20.9395 11.9473C21.6122 12.5173 22 13.3547 22 14.2364V19C22 20.6569 20.6569 22 19 22H17V15H11V22H9C7.34312 22 6 20.6569 6 19V14.2364C6.00003 13.3547 6.38775 12.5173 7.06055 11.9473L12.0605 7.71096Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow154wb2c {
  stroke-opacity: 0.4;
  d: path("M3.1715 12.8116C3.0613 12.5636 3 12.289 3 12L3 7.5417C3 6.9538 3.2586 6.3957 3.7072 6.0157L6.7072 3.474C7.4532 2.842 8.5468 2.842 9.2928 3.474L10.9186 4.8515");
}

</style>
