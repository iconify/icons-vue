<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6cwcmpzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:developer-board" /></template>
<style>
.o6cwcmpzp {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h14q.825 0 1.413.588T20 5v2h2v2h-2v2h2v2h-2v2h2v2h-2v2q0 .825-.587 1.413T18 21zm2-4h5v-4H6zm6-7h4V7h-4zm-6 2h5V7H6zm6 5h4v-6h-4z");
}

</style>
