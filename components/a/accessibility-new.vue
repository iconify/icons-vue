<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e37lkgyjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:accessibility-new" /></template>
<style>
.e37lkgyjc {
  fill: currentColor;
  d: path("M10.588 5.413Q10 4.825 10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6t-1.412-.587M9 22V9q-1.5-.125-3.05-.375T3 8l.5-2q1.95.525 4.15.763T12 7t4.35-.238T20.5 6l.5 2q-1.4.375-2.95.625T15 9v13h-2v-6h-2v6z");
}

</style>
