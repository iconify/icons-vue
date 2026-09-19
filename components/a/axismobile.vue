<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxfj52d6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:axismobile" /></template>
<style>
.cxfj52d6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.835h11.39l12.616-22.143L24 8.165Zm29.695-12.479H24l7.11 12.479H42.5Z");
}

</style>
