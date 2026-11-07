<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ssj12hbqj"/><path class="ryuyobbba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ryuyobbba {
  d: path("m2.707 2.293l5.821 5.821l.017.016l13.162 13.163a.999.999 0 1 1-1.414 1.414L13 15.414v6.355a1 1 0 0 1-2 0v-8.355L7.238 9.653L2.877 7.499a1.001 1.001 0 0 1 .319-1.889L1.293 3.707a.999.999 0 1 1 1.414-1.414M13.931 8.82l6.306-3.114a1 1 0 1 1 .886 1.793l-6.307 3.114a1 1 0 0 1-.885-1.793");
}

.ssj12hbqj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.476 4.234l-.746-.747l3.942-1.946a3 3 0 0 1 1.312-.31h.032c.456.002.904.108 1.312.31l7 3.456A3 3 0 0 1 22 7.687v8.626a3.02 3.02 0 0 1-.619 1.826Zm10.749 13.577l1.493 1.493l-6.39 3.155a3 3 0 0 1-1.312.31h-.032a3 3 0 0 1-1.312-.31l-7-3.456A3 3 0 0 1 2 16.313V7.687c0-1.141.648-2.184 1.672-2.69l1.164-.575Z");
}

</style>
