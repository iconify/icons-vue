<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g220b3b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lab-profile" /></template>
<style>
.g220b3b5c {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0-4h8V6H8zm11.95 12.475L15.9 15.2q-.425-.575-1.05-.887T13.5 14H4V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .125-.012.238t-.038.237M6 22q-.825 0-1.412-.587T4 20v-4h9.5q.25 0 .463.113t.362.312l4.2 5.5q-.125.05-.262.063T18 22z");
}

</style>
