<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwo7aabiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:corporate-fare-outline" /></template>
<style>
.hwo7aabiv {
  fill: currentColor;
  d: path("M2 21V3h10v4h10v14zm2-2h6v-2H4zm0-4h6v-2H4zm0-4h6V9H4zm0-4h6V5H4zm8 12h8V9h-8zm2-6v-2h4v2zm0 4v-2h4v2z");
}

</style>
