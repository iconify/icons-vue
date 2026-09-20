<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ottwb4goy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backup-table-outline-sharp" /></template>
<style>
.ottwb4goy {
  fill: currentColor;
  d: path("M7.5 16H13v-5.5H7.5zm0-6.5h12V4h-12zM14 16h5.5v-5.5H14zm-7.5 1V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
