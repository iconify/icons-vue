<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ynm_7wbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hockey-light" /></template>
<style>
.ynm_7wbij {
  fill: currentColor;
  d: path("M224 154h-94L36.57 44.12a6 6 0 1 0-9.14 7.77L161 209.07a14 14 0 0 0 10.7 4.93H224a14 14 0 0 0 14-14v-32a14 14 0 0 0-14-14m-53.82 47.3l-30-35.3H194v36h-22.3a2 2 0 0 1-1.52-.7M226 200a2 2 0 0 1-2 2h-18v-36h18a2 2 0 0 1 2 2Zm-115.11-18.92a6 6 0 0 0-8.46.68L85.82 201.3a2 2 0 0 1-1.52.7H62v-36h23.2a6 6 0 0 0 0-12H32a14 14 0 0 0-14 14v32a14 14 0 0 0 14 14h52.3a14 14 0 0 0 10.7-4.93l16.6-19.54a6 6 0 0 0-.71-8.45M30 200v-32a2 2 0 0 1 2-2h18v36H32a2 2 0 0 1-2-2m121.43-75.88l68-80a6 6 0 1 1 9.14 7.77l-68 80a6 6 0 0 1-9.14-7.77");
}

</style>
