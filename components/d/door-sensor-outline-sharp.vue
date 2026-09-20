<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hghu97bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-sensor-outline-sharp" /></template>
<style>
.hghu97bjf {
  fill: currentColor;
  d: path("M9 15V5v14zm-2 1h2v3h6V5H9v9H7V3h10v18H7zm5-6q.425 0 .713-.288T13 9t-.288-.712T12 8t-.712.288T11 9t.288.713T12 10m7-7h2v6h-2zm-6 13H4v-2h9z");
}

</style>
