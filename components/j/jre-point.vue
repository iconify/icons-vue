<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sr05k8pnh"/><path class="mwjiphbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jre-point" /></template>
<style>
.mwjiphbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.033 14.178a9.89 9.89 0 0 0-9.443 6.982h18.895a9.89 9.89 0 0 0-9.452-6.982M10.556 26.84a9.89 9.89 0 0 0 9.477 7.121a9.89 9.89 0 0 0 9.477-7.121z");
}

.sr05k8pnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.94 13.02c-4.413-4.413-11.08-5.74-16.872-3.34a15.5 15.5 0 0 0 0 28.64c5.792 2.399 12.459 1.073 16.872-3.34c4.698-4.207 7.812-9.4 12.56-10.98c-4.748-1.582-7.862-6.774-12.56-10.98");
}

</style>
