<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu3i4nbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:5g-outline" /></template>
<style>
.gu3i4nbee {
  fill: currentColor;
  d: path("M3 17v-2h5v-2H3V7h7v2H5v2h3q.825 0 1.413.588T10 13v2q0 .825-.587 1.413T8 17zm18-6v4q0 .825-.587 1.413T19 17h-5q-.825 0-1.412-.587T12 15V9q0-.825.588-1.412T14 7h5q.825 0 1.413.588T21 9h-7v6h5v-2h-2.5v-2z");
}

</style>
