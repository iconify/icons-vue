<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mila7gb6u"/><path class="g5ofzr94s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bird-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g5ofzr94s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 8l3-2c0-1 1-2 3-2s3 1 4 3c1 3 4 6 8 8l-4 1q-1.5 3-6 3c-3 0-5-2-5-5v-4Zm7 11v2m4-2v2M9 7h.01m.99 4c0 2 1 3 2 3");
}

.mila7gb6u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.067 5.42c.271-1.142 1.254-1.891 2.34-2.208A5.7 5.7 0 0 1 9 3c2.581.001 3.845 1.454 4.894 3.553q.033.063.055.131c.236.709.584 1.377.995 2a13 13 0 0 0 1.638 1.984c1.413 1.412 3.082 2.546 4.865 3.438a1 1 0 0 1-.204 1.864l-3.576.894C16.242 19.255 13.641 20 11 20c-3.549-.001-5.999-2.451-6-6v-3.465L2.445 8.832a1 1 0 0 1 0-1.664Z");
}

</style>
