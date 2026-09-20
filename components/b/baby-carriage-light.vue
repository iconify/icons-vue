<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s4d4nn-2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baby-carriage-light" /></template>
<style>
.s4d4nn-2o {
  fill: currentColor;
  d: path("M160 34h-8a14 14 0 0 0-14 14v58H53.52A38.05 38.05 0 0 0 16 74a6 6 0 0 0 0 12a26 26 0 0 1 26 26a78.09 78.09 0 0 0 78 78h40a78 78 0 0 0 0-156m65.71 72H161.1l47.82-38.25A65.66 65.66 0 0 1 225.71 106M152 46h8a65.67 65.67 0 0 1 40 13.53l-50 40V48a2 2 0 0 1 2-2m8 132h-40a66.09 66.09 0 0 1-65.73-60h171.46A66.09 66.09 0 0 1 160 178m-58 46a14 14 0 1 1-14-14a14 14 0 0 1 14 14m104 0a14 14 0 1 1-14-14a14 14 0 0 1 14 14");
}

</style>
