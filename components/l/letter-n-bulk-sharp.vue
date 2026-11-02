<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de_v7eb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-n-bulk-sharp" /></template>
<style>
.de_v7eb0n {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 1 1.848-.53L16 16.513V4a1 1 0 0 1 2 0v16a1 1 0 0 1-1.848.53L8 7.487V20a1 1 0 0 1-2 0Z");
}

</style>
