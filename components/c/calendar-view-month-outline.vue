<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd6ga4bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-view-month-outline" /></template>
<style>
.xd6ga4bjc {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-9h4V6H4zm6 0h4V6h-4zm6 0h4V6h-4zm-8 7v-5H4v5zm2 0h4v-5h-4zm6 0h4v-5h-4z");
}

</style>
