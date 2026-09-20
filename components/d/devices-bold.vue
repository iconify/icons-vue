<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="azid3gpus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:devices-bold" /></template>
<style>
.azid3gpus {
  fill: currentColor;
  d: path("M224 72h-12v-8a28 28 0 0 0-28-28H40a28 28 0 0 0-28 28v88a28 28 0 0 0 28 28h96v12a28 28 0 0 0 28 28h60a28 28 0 0 0 28-28v-92a28 28 0 0 0-28-28M40 156a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h144a4 4 0 0 1 4 4v8h-24a28 28 0 0 0-28 28v56Zm188 36a4 4 0 0 1-4 4h-60a4 4 0 0 1-4-4v-92a4 4 0 0 1 4-4h60a4 4 0 0 1 4 4Zm-104 16a12 12 0 0 1-12 12H88a12 12 0 0 1 0-24h24a12 12 0 0 1 12 12m88-84a12 12 0 0 1-12 12h-12a12 12 0 0 1 0-24h12a12 12 0 0 1 12 12");
}

</style>
