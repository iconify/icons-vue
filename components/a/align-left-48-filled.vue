<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bwi70rnoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-left-48-filled" /></template>
<style>
.bwi70rnoe {
  fill: currentColor;
  d: path("M6.5 5.25a1.25 1.25 0 1 1 2.5 0v37.5a1.25 1.25 0 1 1-2.5 0zM15.75 26a4.25 4.25 0 0 0-4.25 4.25v5.5A4.25 4.25 0 0 0 15.75 40h15A4.25 4.25 0 0 0 35 35.75v-5.5A4.25 4.25 0 0 0 30.75 26zM11.5 12.25v5.5A4.25 4.25 0 0 0 15.75 22H38a4.25 4.25 0 0 0 4.25-4.25v-5.5A4.25 4.25 0 0 0 38 8H15.75a4.25 4.25 0 0 0-4.25 4.25");
}

</style>
