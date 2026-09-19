<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eu4j98bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diode" /></template>
<style>
.eu4j98bcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.75 43.5h16.5m-8.25 0L13.79 25.8h20.43zm8.25-39h-16.5m8.25 0l10.22 17.69H13.79z");
}

</style>
