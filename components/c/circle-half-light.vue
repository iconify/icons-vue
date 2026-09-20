<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vyjchkbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:circle-half-light" /></template>
<style>
.vyjchkbua {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m6 12.2a90 90 0 0 1 20 3.63v172.34a90 90 0 0 1-20 3.63Zm32 8.23a90.5 90.5 0 0 1 20 12.81v137.52a90.5 90.5 0 0 1-20 12.81ZM38 128a90.12 90.12 0 0 1 84-89.8v179.6A90.12 90.12 0 0 1 38 128m160 56.5v-113a89.81 89.81 0 0 1 0 113");
}

</style>
