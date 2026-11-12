<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnxjytb-q"/><path class="v0-jn0bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-duocolor-sharp" /></template>
<style>
.fnxjytb-q {
  stroke-opacity: 0.4;
  d: path("M10 14v-3l5-5l3 3l-5 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0-jn0bvp {
  d: path("M3 3h18v18H3Zm0 14l2-2l6 6");
}

</style>
