<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6--0rxtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:compare-outline" /></template>
<style>
.p6--0rxtf {
  fill: currentColor;
  d: path("M10 23v-2H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h5V1h2v22zm-5-5h5v-6zm9 3v-9l5 6V5h-5V3h5q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
