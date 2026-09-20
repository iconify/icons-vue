<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbl3skaee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airplay-outline-sharp" /></template>
<style>
.qbl3skaee {
  fill: currentColor;
  d: path("M7.423 20L12 15.423L16.577 20zM3 18V4h18v14h-4v-1h3V5H4v12h3v1zm9-6.5");
}

</style>
