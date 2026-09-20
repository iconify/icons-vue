<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqy6klgxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hr-resting" /></template>
<style>
.qqy6klgxx {
  fill: currentColor;
  d: path("M4.366 20v-1h15.23v1zm1.77-8.311q-.575-.542-.843-1.283t-.268-1.523q0-1.623 1.09-2.763Q7.204 4.98 8.8 4.98q.737 0 1.413.287t1.21.816L12 6.66l.577-.558q.535-.529 1.21-.825q.676-.296 1.413-.296q1.603 0 2.702 1.155T19 8.906q0 .779-.288 1.489t-.823 1.269L12.683 16.7q-.14.14-.317.21t-.366.07t-.366-.07t-.317-.21z");
}

</style>
