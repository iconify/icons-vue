<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y17k_toyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-24-filled" /></template>
<style>
.y17k_toyi {
  fill: currentColor;
  d: path("M8.5 13.75A4.25 4.25 0 0 0 12.75 18h1.75v.75A3.25 3.25 0 0 1 11.25 22h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zM18.75 2A3.25 3.25 0 0 1 22 5.25v8.5A3.25 3.25 0 0 1 18.75 17h-6a3.25 3.25 0 0 1-3.25-3.25v-8.5A3.25 3.25 0 0 1 12.75 2z");
}

</style>
