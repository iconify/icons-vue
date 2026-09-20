<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d_f-_2gtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:images-bold" /></template>
<style>
.d_f-_2gtp {
  fill: currentColor;
  d: path("M160 88a16 16 0 1 1 16 16a16 16 0 0 1-16-16m76-32v104a20 20 0 0 1-20 20h-12v20a20 20 0 0 1-20 20H40a20 20 0 0 1-20-20V88a20 20 0 0 1 20-20h20V56a20 20 0 0 1 20-20h136a20 20 0 0 1 20 20m-56 124H80a20 20 0 0 1-20-20V92H44v104h136Zm-21.66-24L124 121.66L89.66 156ZM212 60H84v67.72l25.86-25.86a20 20 0 0 1 28.28 0L192.28 156H212Z");
}

</style>
