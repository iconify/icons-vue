<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gskt1sm_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-6-outline-sharp" /></template>
<style>
.gskt1sm_r {
  fill: currentColor;
  d: path("M11 11V9h3V7H9v10h6v-6zm0 2h2v2h-2zm-8 8V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
