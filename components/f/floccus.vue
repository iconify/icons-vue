<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l5eeusbmt"/><path class="aalwf56de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:floccus" /></template>
<style>
.aalwf56de {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.26 26.434l4.648 4.596l7.478-9.564");
}

.l5eeusbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.783 35.573h23.98c13.015 0 10.837-19.586-2.216-15.243c0-10.876-19.586-10.876-19.586 2.178C2.073 20.33 2.073 35.574 10.783 35.574Z");
}

</style>
