<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="stwvtebkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bowling-ball-fill" /></template>
<style>
.stwvtebkp {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m4 104a12 12 0 1 1 12-12a12 12 0 0 1-12 12m20-36a12 12 0 1 1 12 12a12 12 0 0 1-12-12m20 52a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
