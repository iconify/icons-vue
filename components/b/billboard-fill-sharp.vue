<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amiil1ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:billboard-fill-sharp" /></template>
<style>
.amiil1ble {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-3v5a1 1 0 0 1-2 0v-5H8v5a1 1 0 0 1-2 0v-5H3a1 1 0 0 1-1-1Zm15 3H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2m-4 4H7a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
