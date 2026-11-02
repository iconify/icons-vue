<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfv8xnp-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:figma-fill-round" /></template>
<style>
.kfv8xnp-m {
  fill: currentColor;
  d: path("M15 2a4 4 0 0 1 2.646 7A4 4 0 0 1 13 15.465V18a4 4 0 1 1-6.646-3a4 4 0 0 1 0-6A4 4 0 0 1 9 2Z");
}

</style>
