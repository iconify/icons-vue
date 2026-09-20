<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wutiln8-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gif-2-sharp" /></template>
<style>
.wutiln8-h {
  fill: currentColor;
  d: path("M3 16.5v-9h6.77v1H4v7h4.904v-3H6.712v-1h3.192v5zm9.904 0v-9h1v9zm4 0v-9h6v1h-5v3h4v1h-4v4z");
}

</style>
