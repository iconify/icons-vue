<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyu3_bb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:inbox-rounded" /></template>
<style>
.oyu3_bb8d {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm7-5q.8 0 1.475-.413t1.1-1.087q.15-.225.375-.363t.5-.137H19V5H5v9h3.55q.275 0 .5.138t.375.362q.425.675 1.1 1.088T12 16");
}

</style>
