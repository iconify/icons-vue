<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1kmyhber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-fill-round" /></template>
<style>
.a1kmyhber {
  fill: currentColor;
  d: path("M8 11h8V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H8v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
