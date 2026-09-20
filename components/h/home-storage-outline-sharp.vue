<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hydbnn_uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-storage-outline-sharp" /></template>
<style>
.hydbnn_uc {
  fill: currentColor;
  d: path("M5 21L3 9h18l-2 12zm1.675-2h10.65l1.275-8H5.4zM9 15h6v-2H9zM5 8V6h14v2zm2-3V3h10v2zm-.325 14h10.65z");
}

</style>
