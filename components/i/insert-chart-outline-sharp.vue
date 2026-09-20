<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0_zt8vbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:insert-chart-outline-sharp" /></template>
<style>
.o0_zt8vbz {
  fill: currentColor;
  d: path("M7 17h2v-7H7zm4 0h2V7h-2zm4 0h2v-4h-2zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
