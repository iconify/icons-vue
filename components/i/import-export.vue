<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hquelcb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:import-export" /></template>
<style>
.hquelcb9e {
  fill: currentColor;
  d: path("M9 3L5 6.99h3V14h2V6.99h3zm7 14.01V10h-2v7.01h-3L15 21l4-3.99z");
}

</style>
