<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqpm6nb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-7-5-outline-rounded" /></template>
<style>
.rqpm6nb5w {
  fill: currentColor;
  d: path("M5 19q-.825 0-1.412-.587T3 17V7q0-.825.588-1.412T5 5h14q.825 0 1.413.588T21 7v10q0 .825-.587 1.413T19 19zm0-2h14V7H5zm0 0V7z");
}

</style>
