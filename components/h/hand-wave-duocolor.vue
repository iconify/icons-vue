<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rpb61m-0r"/><path class="zrqnwibjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-wave-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rpb61m-0r {
  stroke-opacity: 0.4;
  d: path("M3.02 5.322a6.5 6.5 0 0 1 5.547-2.297m12.408 12.408a6.5 6.5 0 0 1-2.297 5.546");
}

.zrqnwibjg {
  d: path("m8.291 11.81l1.56-4.286a1.52 1.52 0 0 1 2.856 1.04l.52-1.428a1.52 1.52 0 0 1 2.857 1.04l-.78 2.142a1.52 1.52 0 0 1 2.857 1.04l-2.08 5.713a3.8 3.8 0 0 1-4.87 2.271l-2.857-1.04c-.457-.166-.877-.61-1.168-1.234L4.46 11.224C3.552 9.276 6.474 7.913 7.383 9.86zm4.416-3.246l-1.3 3.57m3.897-1.816l-1.04 2.857");
}

</style>
