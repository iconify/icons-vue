<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy5rscb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:broken-image-rounded" /></template>
<style>
.wy5rscb0c {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-6.6l2.3 2.3q.3.3.7.3t.7-.3l3.3-3.3l3.3 3.3q.3.3.7.3t.7-.3l3.3-3.3l3 3V19q0 .825-.587 1.413T19 21zM5 3h14q.825 0 1.413.588T21 5v6.575l-2.3-2.3q-.3-.3-.7-.3t-.7.3l-3.3 3.3l-3.3-3.3q-.3-.3-.7-.3t-.7.3l-3.3 3.3l-3-3V5q0-.825.588-1.412T5 3");
}

</style>
