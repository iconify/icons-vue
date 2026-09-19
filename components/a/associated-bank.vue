<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cpwca2btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:associated-bank" /></template>
<style>
.cpwca2btj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 23.28c-3.2 4.79-7.93 8.6-13.54 10.84v-9.39C16.07 22.5 20.79 18.69 24 13.89zm0-9.39c3.2 4.79 7.93 8.6 13.54 10.84v-9.39C31.94 13.11 27.21 9.3 24 4.5zm0 18.77c3.2 4.79 7.93 8.6 13.54 10.84v-9.39C31.93 31.88 27.21 28.07 24 23.27zm0 10.83V32.66c-3.2 4.79-7.93 8.6-13.54 10.83z");
}

</style>
