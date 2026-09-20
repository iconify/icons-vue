<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpz65ob4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-3-sharp" /></template>
<style>
.fpz65ob4g {
  fill: currentColor;
  d: path("M9.5 16.5h5v-9h-5v1h4v3h-2.384v1H13.5v3h-4zM4 20V4h16v16z");
}

</style>
