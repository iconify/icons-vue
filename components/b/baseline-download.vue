<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4qgoeo6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-download" /></template>
<style>
.n4qgoeo6x {
  fill: currentColor;
  d: path("M5 20h14v-2H5zM19 9h-4V3H9v6H5l7 7z");
}

</style>
