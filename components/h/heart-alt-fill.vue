<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlmmwbu-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-alt-fill" /></template>
<style>
.vlmmwbu-j {
  fill: currentColor;
  d: path("m12 5.586l.293-.293a5.243 5.243 0 0 1 7.414 7.414l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6a5.243 5.243 0 0 1 7.414-7.414Z");
}

</style>
