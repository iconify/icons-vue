<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi6dh3nku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-5-sharp" /></template>
<style>
.hi6dh3nku {
  fill: currentColor;
  d: path("M9.5 16.5h5v-5h-4v-3h4v-1h-5v5h4v3h-4zM4 20V4h16v16z");
}

</style>
