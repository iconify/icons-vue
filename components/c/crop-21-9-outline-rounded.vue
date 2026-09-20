<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x50kwbcsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-21-9-outline-rounded" /></template>
<style>
.x50kwbcsb {
  fill: currentColor;
  d: path("M4 17q-.825 0-1.412-.587T2 15V9q0-.825.588-1.412T4 7h16q.825 0 1.413.588T22 9v6q0 .825-.587 1.413T20 17zm0-2h16V9H4zm0 0V9z");
}

</style>
