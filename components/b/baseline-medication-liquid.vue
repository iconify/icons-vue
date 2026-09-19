<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aulg3yunn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-medication-liquid" /></template>
<style>
.aulg3yunn {
  fill: currentColor;
  d: path("M3 3h12v2H3zm11 3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m-1 9h-2.5v2.5h-3V15H5v-3h2.5V9.5h3V12H13zm7-9c-1.68 0-3 1.76-3 4c0 1.77.83 3.22 2 3.76V20c0 .55.45 1 1 1s1-.45 1-1v-6.24c1.17-.54 2-1.99 2-3.76c0-2.24-1.32-4-3-4");
}

</style>
