<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thl1oxbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:briefcase-fill" /></template>
<style>
.thl1oxbsx {
  fill: currentColor;
  d: path("M7.099 7a5.003 5.003 0 0 1 9.802 0H19a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3ZM9.17 7h5.66a3.002 3.002 0 0 0-5.66 0");
}

</style>
