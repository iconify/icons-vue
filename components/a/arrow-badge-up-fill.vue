<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v07ribrhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-up-fill" /></template>
<style>
.v07ribrhy {
  fill: currentColor;
  d: path("M20 19c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424l-5-5a.414.414 0 0 0-.586 0l-5 5a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 4 19v-8c0-.265.105-.52.293-.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6A1 1 0 0 1 20 11Z");
}

</style>
