<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lqjmegb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:court-basketball-bold" /></template>
<style>
.lqjmegb4p {
  fill: currentColor;
  d: path("M224 44H32a20 20 0 0 0-20 20v128a20 20 0 0 0 20 20h192a20 20 0 0 0 20-20V64a20 20 0 0 0-20-20m-4 112h-4a28 28 0 0 1 0-56h4ZM36 100h4a28 28 0 0 1 0 56h-4Zm0 80h4a52 52 0 0 0 0-104h-4v-8h80v120H36Zm104 8V68h80v8h-4a52 52 0 0 0 0 104h4v8Z");
}

</style>
