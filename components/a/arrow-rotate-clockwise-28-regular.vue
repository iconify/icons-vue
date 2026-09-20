<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="cnrv5ybde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-28-regular" /></template>
<style>
.cnrv5ybde {
  fill: currentColor;
  d: path("M14 3c6.075 0 11 4.925 11 11c0 4.055-2.195 7.593-5.46 9.5h2.71a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75v-4.5a.75.75 0 0 1 1.5 0v2.613a9.49 9.49 0 0 0 5-8.363a9.5 9.5 0 0 0-19 0A.75.75 0 0 1 3 14C3 7.925 7.925 3 14 3m0 7.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 1.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
