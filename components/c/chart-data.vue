<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-0d0xbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chart-data" /></template>
<style>
.p-0d0xbwv {
  fill: currentColor;
  d: path("m7.4 16l3.05-3.05l2 2L16 11.425V13h2V8h-5v2h1.575l-2.125 2.125l-2-2L6 14.6zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
