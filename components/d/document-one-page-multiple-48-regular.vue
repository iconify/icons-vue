<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xi3qjgefy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-multiple-48-regular" /></template>
<style>
.xi3qjgefy {
  fill: currentColor;
  d: path("M37.498 8.877a4.25 4.25 0 0 1 2.5 3.873v22.5a8.75 8.75 0 0 1-8.75 8.75h-14.5a4.25 4.25 0 0 1-3.873-2.5h18.373a6.25 6.25 0 0 0 6.25-6.25zM31.25 4a4.25 4.25 0 0 1 4.25 4.25v27a4.25 4.25 0 0 1-4.25 4.25h-19A4.25 4.25 0 0 1 8 35.25v-27A4.25 4.25 0 0 1 12.25 4zm-19 2.5a1.75 1.75 0 0 0-1.75 1.75v27c0 .967.784 1.75 1.75 1.75h19A1.75 1.75 0 0 0 33 35.25v-27a1.75 1.75 0 0 0-1.75-1.75zm16 22a1.25 1.25 0 1 1 0 2.5h-13a1.25 1.25 0 1 1 0-2.5zm0-8a1.25 1.25 0 1 1 0 2.5h-13a1.25 1.25 0 1 1 0-2.5zm0-8a1.25 1.25 0 1 1 0 2.5h-13a1.25 1.25 0 1 1 0-2.5z");
}

</style>
