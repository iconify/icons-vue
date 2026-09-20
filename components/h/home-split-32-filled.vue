<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lb06ofbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-split-32-filled" /></template>
<style>
.lb06ofbby {
  fill: currentColor;
  d: path("M18.108 2.776a3.25 3.25 0 0 0-4.216 0l-9.75 8.31A3.25 3.25 0 0 0 3 13.559V26.5A2.5 2.5 0 0 0 5.5 29h21a2.5 2.5 0 0 0 2.5-2.5V13.56a3.25 3.25 0 0 0-1.142-2.473zM17 8v2a1 1 0 1 1-2 0V8a1 1 0 1 1 2 0m-1 6a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m1 8v2a1 1 0 1 1-2 0v-2a1 1 0 1 1 2 0");
}

</style>
