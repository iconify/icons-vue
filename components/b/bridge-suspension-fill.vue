<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oecv0cc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bridge-suspension-fill" /></template>
<style>
.oecv0cc0u {
  fill: currentColor;
  d: path("M7 3v2.831a5.325 5.325 0 0 0 10 0V3a1 1 0 0 1 2 0v2.586l2.707 2.707a.999.999 0 1 1-1.414 1.414L19 8.414V14h2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0v-3H7v3a1 1 0 0 1-2 0v-3H3a1 1 0 0 1 0-2h2V8.414L3.707 9.707a.999.999 0 1 1-1.414-1.414L5 5.586V3a1 1 0 0 1 2 0m0 6.353V14h4v-2.743a7.34 7.34 0 0 1-4-1.904M17 14V9.353a7.34 7.34 0 0 1-4 1.904V14Z");
}

</style>
