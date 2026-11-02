<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-1rycd7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-fill-sharp" /></template>
<style>
.y-1rycd7n {
  fill: currentColor;
  d: path("M19 5a1 1 0 0 1 1 1v9.171a3 3 0 1 1-2 0V7h-4.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L13.414 5ZM6 8.829V17h4.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L10.586 19H5a1 1 0 0 1-1-1V8.829a3 3 0 1 1 2 0");
}

</style>
