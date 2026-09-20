<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtg7lacdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4k" /></template>
<style>
.jtg7lacdv {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13zm-3.5 0H11v-1.5h1V12h-1V9H9.5v3H8V9H6.5v4.5h3zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
