<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6wsozbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-list" /></template>
<style>
.m6wsozbtw {
  fill: currentColor;
  d: path("M16 21q-.825 0-1.412-.587T14 19v-4q0-.825.588-1.412T16 13h4q.825 0 1.413.588T22 15v4q0 .825-.587 1.413T20 21zM2 18v-2h9v2zm14-7q-.825 0-1.412-.587T14 9V5q0-.825.588-1.412T16 3h4q.825 0 1.413.588T22 5v4q0 .825-.587 1.413T20 11zM2 8V6h9v2z");
}

</style>
