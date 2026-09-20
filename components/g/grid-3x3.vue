<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd1iribgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-3x3" /></template>
<style>
.sd1iribgt {
  fill: currentColor;
  d: path("M9 19v-4H5v-1h4v-4H5V9h4V5h1v4h4V5h1v4h4v1h-4v4h4v1h-4v4h-1v-4h-4v4zm1-5h4v-4h-4z");
}

</style>
