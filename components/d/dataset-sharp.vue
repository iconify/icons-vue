<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzhcejhfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dataset-sharp" /></template>
<style>
.jzhcejhfi {
  fill: currentColor;
  d: path("M3 21V3h18v18zm4-10h4V7H7zm6 0h4V7h-4zm-6 6h4v-4H7zm6 0h4v-4h-4z");
}

</style>
