<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iebu0_9tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-4-sharp" /></template>
<style>
.iebu0_9tw {
  fill: currentColor;
  d: path("M3 21V3h18v18zm10-4h2V7h-2v4h-2V7H9v6h4z");
}

</style>
