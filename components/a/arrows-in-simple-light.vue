<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v-jxs4b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-simple-light" /></template>
<style>
.v-jxs4b_g {
  fill: currentColor;
  d: path("M212.24 52.24L158.48 106H192a6 6 0 0 1 0 12h-48a6 6 0 0 1-6-6V64a6 6 0 0 1 12 0v33.52l53.76-53.76a6 6 0 0 1 8.48 8.48M112 138H64a6 6 0 0 0 0 12h33.52l-53.76 53.76a6 6 0 1 0 8.48 8.48L106 158.48V192a6 6 0 0 0 12 0v-48a6 6 0 0 0-6-6");
}

</style>
