<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iuwgo5_3k"/><path class="oo4oedcbq"/><path class="zbpan-bvy"/><path class="yebcb12-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-wave-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iuwgo5_3k {
  stroke-linejoin: round;
  d: path("M18 19.5V18C18 17.1716 17.3284 16.5 16.5 16.5H14.4444H10.9444C8.45916 16.5 6.44444 14.4853 6.44444 12C6.44444 9.51472 8.45916 7.5 10.9444 7.5H14.4444H16.5C17.3284 7.5 18 6.82843 18 6V4.5C18 3.67157 17.3284 3 16.5 3H14.4444H11C6.02943 3 2 7.02944 2 12C2 16.9706 6.02944 21 11 21H14.4444H16.5C17.3284 21 18 20.3284 18 19.5Z");
}

.oo4oedcbq {
  stroke-linejoin: round;
  d: path("M14.4443 3V7.5M14.4443 16.5V21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yebcb12-h {
  d: path("M19.5 9C19.5 9 20 9.9 20 12C20 14.1 19.5 15 19.5 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zbpan-bvy {
  d: path("M21.5 6C21.5 6 23 7.8 23 12C23 16.2 21.5 18 21.5 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
