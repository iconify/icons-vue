<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrlkc9bnf"/><path class="e2c9xqbhi"/><path class="lerbluboq"/><path class="ylnvyeb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-hours-outline-regular" /></template>
<style>
.e2c9xqbhi {
  d: path("M12 7v5h4");
}

.lerbluboq {
  d: path("M17 4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.ylnvyeb_w {
  d: path("M19 2v4");
}

</style>
