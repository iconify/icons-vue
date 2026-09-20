<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mq5rujfwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:film-script" /></template>
<style>
.mq5rujfwz {
  fill: currentColor;
  d: path("M200 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16m0 192H56V40h144zM96 76a12 12 0 1 1-12-12a12 12 0 0 1 12 12m0 104a12 12 0 1 1-12-12a12 12 0 0 1 12 12m0-52a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
