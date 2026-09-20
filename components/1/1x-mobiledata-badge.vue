<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-0pdjbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:1x-mobiledata-badge" /></template>
<style>
.z-0pdjbgg {
  fill: currentColor;
  d: path("M3 21q-.825 0-1.412-.587T1 19V5q0-.825.588-1.412T3 3h18q.825 0 1.413.588T23 5v14q0 .825-.587 1.413T21 21zm4-4h2V7H5v2h2zm4.5 0h2l1.75-3.175L17 17h2l-2.75-5L19 7h-2l-1.75 3.175L13.5 7h-2l2.75 5z");
}

</style>
