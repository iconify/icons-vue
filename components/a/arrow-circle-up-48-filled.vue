<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fe7n-4vos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-48-filled" /></template>
<style>
.fe7n-4vos {
  fill: currentColor;
  d: path("M24 44C12.954 44 4 35.046 4 24S12.954 4 24 4s20 8.954 20 20s-8.954 20-20 20m-8.634-19.866a1.25 1.25 0 0 0 1.768 0l5.616-5.616V32.75a1.25 1.25 0 1 0 2.5 0V18.518l5.616 5.616a1.25 1.25 0 0 0 1.768-1.768l-7.75-7.75a1.25 1.25 0 0 0-1.768 0l-7.75 7.75a1.25 1.25 0 0 0 0 1.768");
}

</style>
