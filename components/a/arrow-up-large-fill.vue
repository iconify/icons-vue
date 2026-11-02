<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymnavtb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-large-fill" /></template>
<style>
.ymnavtb7o {
  fill: currentColor;
  d: path("M13 5.414V21a1 1 0 0 1-2 0V5.414L6.707 9.707a.999.999 0 1 1-1.414-1.414l6-6a1 1 0 0 1 1.414 0l6 6a.999.999 0 1 1-1.414 1.414Z");
}

</style>
