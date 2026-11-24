<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chw8qebkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-minus-corner-fill-sharp" /></template>
<style>
.chw8qebkr {
  fill: currentColor;
  d: path("M22 5v3H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1M2 10h8v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm11 5h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
