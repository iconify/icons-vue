<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vub_5oz5o"/><path class="g_loohbfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-minus-duotone" /></template>
<style>
.g_loohbfa {
  d: path("M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7M16 17L22 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vub_5oz5o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3H19C21.2091 3 23 4.79086 23 7V10C23 10.5523 22.5523 11 22 11H16C14.3431 11 13 12.3431 13 14V20C13 20.5523 12.5523 21 12 21H5C2.79086 21 1 19.2091 1 17V7C1 4.79086 2.79086 3 5 3Z");
  stroke: none;
}

</style>
