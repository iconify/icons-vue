<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8n0e3bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-24-regular" /></template>
<style>
.k8n0e3bmp {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM4.5 17.75c0 .966.784 1.75 1.75 1.75h5.25v-10h-7zM13 16v3.5h4.75a1.75 1.75 0 0 0 1.75-1.75V16zm0-1.5h6.5V6.25a1.75 1.75 0 0 0-1.75-1.75H13zm-6.75-10A1.75 1.75 0 0 0 4.5 6.25V8h7V4.5z");
}

</style>
