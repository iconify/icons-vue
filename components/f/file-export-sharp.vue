<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj0u_-b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-export-sharp" /></template>
<style>
.qj0u_-b8s {
  fill: currentColor;
  d: path("m5.454 21.664l-.688-.714l3.45-3.45H5.234v-1h4.669v4.67h-1v-2.957zM12.289 21v-6.884H5V3h9.5L19 7.5V21zM14 8h4l-4-4l4 4l-4-4z");
}

</style>
