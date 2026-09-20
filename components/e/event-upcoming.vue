<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg224mbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-upcoming" /></template>
<style>
.eg224mbgy {
  fill: currentColor;
  d: path("M15 22v-2h4V10H5v4H3V6q0-.825.588-1.412T5 4h1V2h2v2h8V2h2v2h1q.825 0 1.413.588T21 6v14q0 .825-.587 1.413T19 22zm-7 2l-1.4-1.4L9.175 20H1v-2h8.175L6.6 15.4L8 14l5 5z");
}

</style>
