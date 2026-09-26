<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dnn4w35hm"/><path class="d8meufkqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-fill" /></template>
<style>
.d8meufkqa {
  d: path("M2 12.625L11.5618 17.2864C11.8384 17.4212 12.1616 17.4212 12.4382 17.2864L22 12.625M2 17.2375L11.5618 21.8989C11.8384 22.0337 12.1616 22.0337 12.4382 21.8989L22 17.2375");
}

.dnn4w35hm {
  fill: currentColor;
  d: path("M12.8764 1.2022L21.8764 5.5897C22.5639 5.9249 23 6.6227 23 7.3875C23 8.1523 22.5639 8.8501 21.8764 9.1853L12.8764 13.5728C12.6034 13.7058 12.3037 13.775 12 13.775C11.6963 13.775 11.3966 13.7058 11.1236 13.5728L2.1236 9.1853C1.4361 8.8501 1 8.1523 1 7.3875C1 6.6227 1.4361 5.9249 2.1236 5.5897L11.1236 1.2022C11.3966 1.0692 11.6963 1 12 1C12.3037 1 12.6034 1.0692 12.8764 1.2022Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
