<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyz2z7bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bank-fill-sharp" /></template>
<style>
.oyz2z7bvl {
  fill: currentColor;
  d: path("M21.406 6.086A1 1 0 0 1 21 8H3a1 1 0 0 1-.406-1.914l9-4a1 1 0 0 1 .812 0ZM7 17a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0ZM3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
