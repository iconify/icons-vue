<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mgqoytbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-down-light" /></template>
<style>
.mgqoytbru {
  fill: currentColor;
  d: path("M229.54 133.7A6 6 0 0 0 224 130h-42V48a14 14 0 0 0-14-14H88a14 14 0 0 0-14 14v82H32a6 6 0 0 0-4.24 10.24l96 96a6 6 0 0 0 8.48 0l96-96a6 6 0 0 0 1.3-6.54M128 223.51L46.49 142H80a6 6 0 0 0 6-6V48a2 2 0 0 1 2-2h80a2 2 0 0 1 2 2v88a6 6 0 0 0 6 6h33.51Z");
}

</style>
