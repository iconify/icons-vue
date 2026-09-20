<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig1csrbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:explicit-outline-sharp" /></template>
<style>
.ig1csrbwl {
  fill: currentColor;
  d: path("M9 17h6v-2h-4v-2h4v-2h-4V9h4V7H9zm-6 4V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
