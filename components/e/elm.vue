<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cdauidgco"><path class="b9tp89bqs"/><path class="g7it7gb8y"/><path class="y0e-g4b7f"/><path class="lcumayeoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:elm" /></template>
<style>
.b9tp89bqs {
  d: path("m8.529 256l119.399-119.399L247.327 256zM0 8.673l119.399 119.399L0 247.471z");
}

.cdauidgco {
  fill: var(--svg-color--1293d8, #1293d8);
}

.g7it7gb8y {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M136.595 0H256v119.405z");
}

.lcumayeoa {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M8.529.144h110.87l52.024 52.024H60.553zm174.834 63.964l-55.435 55.436l-55.436-55.436zm72.493 183.363l-55.436-55.435l55.436-55.435z");
}

.y0e-g4b7f {
  d: path("m136.456 128.072l55.436 55.436l55.435-55.436l-55.435-55.435z");
}

</style>
