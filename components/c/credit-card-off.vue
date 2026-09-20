<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h04rzoyuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-card-off" /></template>
<style>
.h04rzoyuf {
  fill: currentColor;
  d: path("M21.775 18.925L14.85 12H20V8h-9.15l-4-4H20q.825 0 1.413.588T22 6v12q0 .25-.05.488t-.175.437M4 12h5.15l-4-4H4zm16.45 11.3l-3.3-3.3H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l2 2H3.15L.65 3.5l1.425-1.425l19.8 19.8z");
}

</style>
