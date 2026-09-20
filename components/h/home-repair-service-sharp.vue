<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctw4cr3yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-repair-service-sharp" /></template>
<style>
.ctw4cr3yt {
  fill: currentColor;
  d: path("M8.5 8.462h7V6h-7zM3 19v-4.77h3.385v1h1v-1h9.23v1h1v-1H21V19zm0-5.538v-5h4.5V5h9v3.462H21v5h-3.384V12.23h-1v1.23H7.385v-1.23h-1v1.23z");
}

</style>
