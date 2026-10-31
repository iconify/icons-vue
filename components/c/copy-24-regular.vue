<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe5d-j8-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-24-regular" /></template>
<style>
.pe5d-j8-c {
  fill: currentColor;
  d: path("M8.5 8.5H5.25a1.75 1.75 0 0 0-1.75 1.75v8.5c0 .966.784 1.75 1.75 1.75h6A1.75 1.75 0 0 0 13 18.75V18h1.5v.75A3.25 3.25 0 0 1 11.25 22h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zM18.75 2A3.25 3.25 0 0 1 22 5.25v8.5A3.25 3.25 0 0 1 18.75 17h-6a3.25 3.25 0 0 1-3.25-3.25v-8.5A3.25 3.25 0 0 1 12.75 2zm-6 1.5A1.75 1.75 0 0 0 11 5.25v8.5c0 .966.784 1.75 1.75 1.75h6a1.75 1.75 0 0 0 1.75-1.75v-8.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
