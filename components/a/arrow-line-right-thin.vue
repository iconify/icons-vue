<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pw2b-d9qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-right-thin" /></template>
<style>
.pw2b-d9qf {
  fill: currentColor;
  d: path("M186.83 125.17a4 4 0 0 1 0 5.66l-72 72a4 4 0 0 1-5.66-5.66L174.34 132H32a4 4 0 0 1 0-8h142.34l-65.17-65.17a4 4 0 0 1 5.66-5.66ZM216 36a4 4 0 0 0-4 4v176a4 4 0 0 0 8 0V40a4 4 0 0 0-4-4");
}

</style>
