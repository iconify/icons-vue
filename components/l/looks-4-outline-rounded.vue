<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9thers_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-4-outline-rounded" /></template>
<style>
.e9thers_u {
  fill: currentColor;
  d: path("M13 13v3q0 .425.288.713T14 17t.713-.288T15 16V8q0-.425-.288-.712T14 7t-.712.288T13 8v3h-2V8q0-.425-.288-.712T10 7t-.712.288T9 8v4q0 .425.288.713T10 13zm-8 8q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
