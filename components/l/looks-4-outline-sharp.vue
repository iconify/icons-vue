<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxa7ohbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-4-outline-sharp" /></template>
<style>
.bxa7ohbuw {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm0 0V5zm8-2h2V7h-2v4h-2V7H9v6h4z");
}

</style>
