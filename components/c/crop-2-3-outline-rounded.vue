<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v83gghf6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-2-3-outline-rounded" /></template>
<style>
.v83gghf6a {
  fill: currentColor;
  d: path("M8 22q-.825 0-1.412-.587T6 20V4q0-.825.588-1.412T8 2h8q.825 0 1.413.588T18 4v16q0 .825-.587 1.413T16 22zm0-2h8V4H8zm0 0V4z");
}

</style>
