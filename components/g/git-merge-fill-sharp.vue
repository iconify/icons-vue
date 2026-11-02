<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcbljub4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-merge-fill-sharp" /></template>
<style>
.gcbljub4e {
  fill: currentColor;
  d: path("M6.104 8.79A3.01 3.01 0 0 0 9 11h7.171a3 3 0 1 1 0 2H9a5 5 0 0 1-3-.999v3.17a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2.104-.039");
}

</style>
