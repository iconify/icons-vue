<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6knuub2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:key-command-24-regular" /></template>
<style>
.w6knuub2k {
  fill: currentColor;
  d: path("M6.25 4.5C7.216 4.5 8 5.284 8 6.25V8H6.25a1.75 1.75 0 1 1 0-3.5M9.5 8V6.25A3.25 3.25 0 1 0 6.25 9.5H8v5H6.25a3.25 3.25 0 1 0 3.25 3.25V16h5v1.75a3.25 3.25 0 1 0 3.25-3.25H16v-5h1.75a3.25 3.25 0 1 0-3.25-3.25V8zm0 1.5h5v5h-5zM16 8V6.25A1.75 1.75 0 1 1 17.75 8zm0 8h1.75A1.75 1.75 0 1 1 16 17.75zm-8 0v1.75A1.75 1.75 0 1 1 6.25 16z");
}

</style>
