<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_w7_5kaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ice-cream-fill" /></template>
<style>
.v_w7_5kaa {
  fill: currentColor;
  d: path("M6.059 7.151a6.001 6.001 0 0 1 11.882 0A3 3 0 0 1 19.829 11H4.171a3 3 0 0 1 1.888-3.849M17.588 13l-4.714 8.486a1 1 0 0 1-1.748 0L6.412 13Z");
}

</style>
