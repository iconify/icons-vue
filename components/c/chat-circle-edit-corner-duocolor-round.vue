<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vniq9i6ae"/><path class="bmq-ygpux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-edit-corner-duocolor-round" /></template>
<style>
.bmq-ygpux {
  d: path("m8 20l-5 1l1-5a8.944 8.944 0 1 1 16-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vniq9i6ae {
  stroke-opacity: 0.4;
  d: path("M13 21v-3l5-5l3 3l-5 5Z");
}

</style>
