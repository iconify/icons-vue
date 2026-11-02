<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bk7g11b-o"/><path class="c3tl3cc2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:feather-duotone-sharp" /></template>
<style>
.bk7g11b-o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m19.707 11.707l-6 6A1 1 0 0 1 13 18H7a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707l6-6a5.243 5.243 0 0 1 7.414 7.414");
}

.c3tl3cc2c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 5a4.243 4.243 0 0 1 6 6l-6 6H7v-6ZM4 20L16 8m1 5h-6");
}

.ft5dv1b6b {
  fill: none;
}

</style>
