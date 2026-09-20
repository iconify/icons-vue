<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="baf214bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-work-week-32-filled" /></template>
<style>
.baf214bta {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-14 6A2.5 2.5 0 0 0 8 11.5v4a2.5 2.5 0 0 0 2.5 2.5h11a2.5 2.5 0 0 0 2.5-2.5v-4A2.5 2.5 0 0 0 21.5 9zm11 2a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5z");
}

</style>
