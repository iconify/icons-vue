<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2rhhpjrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:css-outline" /></template>
<style>
.q2rhhpjrq {
  fill: currentColor;
  d: path("M10.5 15q-.425 0-.712-.288T9.5 14v-1H11v.5h2v-1h-2.5q-.425 0-.712-.288T9.5 11.5V10q0-.425.288-.712T10.5 9h3q.425 0 .713.288T14.5 10v1H13v-.5h-2v1h2.5q.425 0 .713.288t.287.712V14q0 .425-.288.713T13.5 15zm6.5 0q-.425 0-.712-.288T16 14v-1h1.5v.5h2v-1H17q-.425 0-.712-.288T16 11.5V10q0-.425.288-.712T17 9h3q.425 0 .713.288T21 10v1h-1.5v-.5h-2v1H20q.425 0 .713.288T21 12.5V14q0 .425-.288.713T20 15zM4 15q-.425 0-.712-.288T3 14v-4q0-.425.288-.712T4 9h3q.425 0 .713.288T8 10v1H6.5v-.5h-2v3h2V13H8v1q0 .425-.288.713T7 15z");
}

</style>
