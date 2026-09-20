<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fis863b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-repair-service-outline" /></template>
<style>
.fis863b7z {
  fill: currentColor;
  d: path("M2 20V10q0-.825.588-1.412T4 8h3V6q0-.825.588-1.412T9 4h6q.825 0 1.413.588T17 6v2h3q.825 0 1.413.588T22 10v10zm6-5v1H6v-1H4v3h16v-3h-2v1h-2v-1zm-4-5v3h2v-1h2v1h8v-1h2v1h2v-3zm5-2h6V6H9z");
}

</style>
