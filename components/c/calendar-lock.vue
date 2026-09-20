<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anqa9ub-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-lock" /></template>
<style>
.anqa9ub-v {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h1V2h2v2h8V2h2v2h1q.825 0 1.413.588T21 6v6h-2v-2H5v10h9v2zm11.85 0q-.35 0-.6-.25t-.25-.6v-3.3q0-.35.25-.6t.6-.25H17v-1q0-.825.588-1.412T19 14t1.413.588T21 16v1h.15q.35 0 .6.25t.25.6v3.3q0 .35-.25.6t-.6.25zM18 17h2v-1q0-.425-.288-.712T19 15t-.712.288T18 16z");
}

</style>
