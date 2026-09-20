<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnmkcqdsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-fusiontable" /></template>
<style>
.mnmkcqdsx {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM19 7.25l-6.05 6.8L9 10.1l-4 4v2.85l4-4L13.05 17L19 10.25z");
}

</style>
