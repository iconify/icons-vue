<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfmkfizvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-i-bulk-sharp" /></template>
<style>
.rfmkfizvb {
  fill: currentColor;
  d: path("M12 3h3a1 1 0 0 1 0 2h-2v14h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2h2V5H9a1 1 0 0 1 0-2Z");
}

</style>
