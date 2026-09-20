<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3qvmrbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-chart-outline-sharp" /></template>
<style>
.s3qvmrbhg {
  fill: currentColor;
  d: path("M7.73 16.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
