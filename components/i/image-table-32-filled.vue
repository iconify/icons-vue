<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uyyno7ejm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-table-32-filled" /></template>
<style>
.uyyno7ejm {
  fill: currentColor;
  d: path("M8 3h-.5A4.5 4.5 0 0 0 3 7.5V8h5zm-5 7v12h5V10zm7-2h12V3H10zm14-5v5h5v-.5A4.5 4.5 0 0 0 24.5 3zm5 7h-5v12h5zm0 14h-5v5h.5a4.5 4.5 0 0 0 4.5-4.5zm-7 5v-5H10v5zM8 29v-5H3v.5A4.5 4.5 0 0 0 7.5 29zm2-8.535l4.232-4.233a2.5 2.5 0 0 1 3.536 0L22 20.465V10H10zM17 13a2 2 0 1 1 4 0a2 2 0 0 1-4 0m3.707 9l-4.353-4.354a.5.5 0 0 0-.708 0L11.293 22z");
}

</style>
