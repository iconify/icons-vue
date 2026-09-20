<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrrewpbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grouped-bar-chart-outline-sharp" /></template>
<style>
.nrrewpbye {
  fill: currentColor;
  d: path("M5 19V8.712h3V19zm4.385 0v-5.654h3V19zM16 19V5h3v14z");
}

</style>
