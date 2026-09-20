<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el2jtsbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-view-day-outline-sharp" /></template>
<style>
.el2jtsbtf {
  fill: currentColor;
  d: path("M4 19.385v-1h16v1zM4 16V8h16v8zm1-1h14V9H5zM4 5.615v-1h16v1zM5 15V9z");
}

</style>
