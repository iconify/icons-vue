<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4nr9eq7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:analytics-outline-sharp" /></template>
<style>
.d4nr9eq7q {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm2-2h2v-5H7zm8 0h2V7h-2zm-4 0h2v-3h-2zm0-5h2v-2h-2zm-6 7V5z");
}

</style>
