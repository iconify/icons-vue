<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5a5oubgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-imagesearch-roller" /></template>
<style>
.d5a5oubgj {
  fill: currentColor;
  d: path("M20 2v6H6V6H4v4h10v5h2v8h-6v-8h2v-3H2V4h4V2");
}

</style>
