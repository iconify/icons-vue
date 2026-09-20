<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lk3zhdcsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-split-fill" /></template>
<style>
.lk3zhdcsq {
  fill: currentColor;
  d: path("m229.66 189.66l-32 32a8 8 0 0 1-11.32 0l-32-32A8 8 0 0 1 160 176h24v-36.69l-56-56l-56 56V176h24a8 8 0 0 1 5.66 13.66l-32 32a8 8 0 0 1-11.32 0l-32-32A8 8 0 0 1 32 176h24v-40a8 8 0 0 1 2.34-5.66L120 68.69V24a8 8 0 0 1 16 0v44.69l61.66 61.65A8 8 0 0 1 200 136v40h24a8 8 0 0 1 5.66 13.66");
}

</style>
