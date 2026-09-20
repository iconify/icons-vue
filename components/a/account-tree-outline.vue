<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d04nunr4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-tree-outline" /></template>
<style>
.d04nunr4j {
  fill: currentColor;
  d: path("M15.5 20.5v-3h-4v-10h-3v3h-6v-7h6v3h7v-3h6v7h-6v-3h-3v9h3v-3h6v7zm-12-16v5zm13 10v5zm0-10v5zm0 5h4v-5h-4zm0 10h4v-5h-4zm-13-10h4v-5h-4z");
}

</style>
