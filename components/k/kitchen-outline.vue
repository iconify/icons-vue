<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8cbysb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:kitchen-outline" /></template>
<style>
.z8cbysb0g {
  fill: currentColor;
  d: path("M8 8V5h2v3zm0 9v-5h2v5zm-2 5q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12v-9H6zM6 9h12V4H6z");
}

</style>
