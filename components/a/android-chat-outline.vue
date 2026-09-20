<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g23c5w1et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-chat-outline" /></template>
<style>
.g23c5w1et {
  fill: currentColor;
  d: path("M2 22V9q0-.825.588-1.413Q3.175 7 4 7h2v5q0 .825.588 1.412Q7.175 14 8 14h10v3q0 .825-.587 1.413Q16.825 19 16 19H5Zm16-8V9q0-.825-.587-1.413Q16.825 7 16 7H6V4q0-.825.588-1.413Q7.175 2 8 2h12q.825 0 1.413.587Q22 3.175 22 4v8q0 .825-.587 1.412Q20.825 14 20 14Zm-6-3.5Zm0 0Z");
}

</style>
