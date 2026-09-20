<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0a2sfbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lists-outline-rounded" /></template>
<style>
.k0a2sfbvl {
  fill: currentColor;
  d: path("M10 20q-.825 0-1.412-.587T8 18t.588-1.412T10 16h10q.825 0 1.413.588T22 18t-.587 1.413T20 20zm0-6q-.825 0-1.412-.587T8 12t.588-1.412T10 10h10q.825 0 1.413.588T22 12t-.587 1.413T20 14zm0-6q-.825 0-1.412-.587T8 6t.588-1.412T10 4h10q.825 0 1.413.588T22 6t-.587 1.413T20 8zm-7.413-.587Q2 6.825 2 6t.588-1.412T4 4t1.413.588T6 6t-.587 1.413T4 8t-1.412-.587M4 14q-.825 0-1.412-.587T2 12t.588-1.412T4 10t1.413.588T6 12t-.587 1.413T4 14m0 6q-.825 0-1.412-.587T2 18t.588-1.412T4 16t1.413.588T6 18t-.587 1.413T4 20");
}

</style>
