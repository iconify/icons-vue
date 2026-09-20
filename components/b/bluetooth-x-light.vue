<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lazaz1bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bluetooth-x-light" /></template>
<style>
.lazaz1bxm {
  fill: currentColor;
  d: path("M179.6 171.2L122 128l25.6-19.2a6 6 0 1 0-7.2-9.6L118 116V44l22.4 16.8a6 6 0 1 0 7.2-9.6l-32-24A6 6 0 0 0 106 32v84L51.6 75.2a6 6 0 0 0-7.2 9.6L102 128l-57.6 43.2a6 6 0 0 0 7.2 9.6L106 140v84a6 6 0 0 0 9.6 4.8l64-48a6 6 0 0 0 0-9.6M118 212v-72l48 36ZM236.24 99.76a6 6 0 1 1-8.48 8.48L208 88.49l-19.76 19.75a6 6 0 0 1-8.48-8.48L199.51 80l-19.75-19.76a6 6 0 0 1 8.48-8.48L208 71.51l19.76-19.75a6 6 0 0 1 8.48 8.48L216.49 80Z");
}

</style>
