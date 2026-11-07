<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o6njlubaq"/><path class="gd1b5kq4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blocks-duocolor-sharp" /></template>
<style>
.gd1b5kq4f {
  d: path("M3 7h7v7h7v7H3zm7 7v7m-7-7h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6njlubaq {
  stroke-opacity: 0.4;
  d: path("M14 3h7v7h-7Z");
}

</style>
