<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4v-ekbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-u-fill-sharp" /></template>
<style>
.q4v-ekbdh {
  fill: currentColor;
  d: path("M8 16a4 4 0 0 0 8 0V4a1 1 0 0 1 2 0v12a6 6 0 1 1-12 0V4a1 1 0 0 1 2 0Z");
}

</style>
