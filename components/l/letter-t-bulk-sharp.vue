<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwifcgbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-t-bulk-sharp" /></template>
<style>
.mwifcgbsb {
  fill: currentColor;
  d: path("M12 3h6a1 1 0 0 1 0 2h-5v15a1 1 0 0 1-2 0V5H6a1 1 0 0 1 0-2Z");
}

</style>
