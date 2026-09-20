<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="offfy4bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dots-six-vertical-fill" /></template>
<style>
.offfy4bfy {
  fill: currentColor;
  d: path("M192 16H64a16 16 0 0 0-16 16v192a16 16 0 0 0 16 16h128a16 16 0 0 0 16-16V32a16 16 0 0 0-16-16m-92 184a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-60a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-60a12 12 0 1 1 12-12a12 12 0 0 1-12 12m56 120a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-60a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-60a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
