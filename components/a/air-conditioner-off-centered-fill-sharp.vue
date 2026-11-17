<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vux6_f6ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-conditioner-off-centered-fill-sharp" /></template>
<style>
.vux6_f6ol {
  fill: currentColor;
  d: path("M2 8a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 4a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Z");
}

</style>
