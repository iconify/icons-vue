<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0tz1cqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-from-line-fill-round" /></template>
<style>
.zc0tz1cqs {
  fill: currentColor;
  d: path("M6 3h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m1.293 13.707a.999.999 0 1 1 1.414-1.414L11 17.586V8a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0Z");
}

</style>
