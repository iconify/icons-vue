<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2fy8f0su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grain-rounded" /></template>
<style>
.m2fy8f0su {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.412-.587T4 18t.588-1.412T6 16t1.413.588T8 18t-.587 1.413T6 20m8 0q-.825 0-1.412-.587T12 18t.588-1.412T14 16t1.413.588T16 18t-.587 1.413T14 20m-4-4q-.825 0-1.412-.587T8 14t.588-1.412T10 12t1.413.588T12 14t-.587 1.413T10 16m8 0q-.825 0-1.412-.587T16 14t.588-1.412T18 12t1.413.588T20 14t-.587 1.413T18 16M6 12q-.825 0-1.412-.587T4 10t.588-1.412T6 8t1.413.588T8 10t-.587 1.413T6 12m8 0q-.825 0-1.412-.587T12 10t.588-1.412T14 8t1.413.588T16 10t-.587 1.413T14 12m-4-4q-.825 0-1.412-.587T8 6t.588-1.412T10 4t1.413.588T12 6t-.587 1.413T10 8m8 0q-.825 0-1.412-.587T16 6t.588-1.412T18 4t1.413.588T20 6t-.587 1.413T18 8");
}

</style>
