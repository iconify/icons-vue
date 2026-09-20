<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnca3mbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flowchart-sharp" /></template>
<style>
.xnca3mbhe {
  fill: currentColor;
  d: path("M16 20q-.425 0-.712-.288T15 19v-1h-3q-.425 0-.712-.288T11 17v-4H9v1q0 .425-.288.713T8 15H3q-.425 0-.712-.288T2 14v-4q0-.425.288-.712T3 9h5q.425 0 .713.288T9 10v1h2V7q0-.425.288-.712T12 6h3V5q0-.425.288-.712T16 4h5q.425 0 .713.288T22 5v4q0 .425-.288.713T21 10h-5q-.425 0-.712-.288T15 9V8h-2v8h2v-1q0-.425.288-.712T16 14h5q.425 0 .713.288T22 15v4q0 .425-.288.713T21 20z");
}

</style>
