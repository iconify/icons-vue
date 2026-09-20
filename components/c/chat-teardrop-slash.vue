<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pu2aygvpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-teardrop-slash" /></template>
<style>
.pu2aygvpg {
  fill: currentColor;
  d: path("M53.92 34.62a8 8 0 1 0-11.84 10.76l13.18 14.5A99.4 99.4 0 0 0 32 124v84a16 16 0 0 0 16 16h84a100.33 100.33 0 0 0 56.53-17.53l13.55 14.91a8 8 0 1 0 11.84-10.76ZM132 208H48v-84a83.46 83.46 0 0 1 18.15-52.15l111.51 122.66A83 83 0 0 1 132 208m100-84a99.87 99.87 0 0 1-14.35 51.65a8 8 0 0 1-13.7-8.28A84 84 0 0 0 95.66 48.25a8 8 0 0 1-6.94-14.42A100 100 0 0 1 232 124");
}

</style>
