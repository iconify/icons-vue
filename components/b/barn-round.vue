<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5schyb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-round" /></template>
<style>
.o5schyb9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 21H4v-9.667a4 4 0 0 1 .8-2.4l1.73-2.306a4 4 0 0 1 1.142-1.03l2.27-1.362a4 4 0 0 1 4.116 0l2.27 1.362a4 4 0 0 1 1.142 1.03l1.73 2.306a4 4 0 0 1 .8 2.4zM3 21h18M9 21v-3a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3m-5-11a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
