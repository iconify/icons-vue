<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6r7r6-gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:couch-32-regular" /></template>
<style>
.u6r7r6-gv {
  fill: currentColor;
  d: path("M9 6a4 4 0 0 0-4 4v1.256A4.5 4.5 0 0 0 2 15.5V20a4 4 0 0 0 3 3.874V26a1 1 0 1 0 2 0v-2h18v2a1 1 0 1 0 2 0v-2.126c1.725-.444 3-2.01 3-3.874v-4.5a4.5 4.5 0 0 0-3-4.244V10a4 4 0 0 0-4-4zm17 16H6a2 2 0 0 1-2-2v-4.5a2.5 2.5 0 0 1 5 0v.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-.5a2.5 2.5 0 0 1 5 0V20a2 2 0 0 1-2 2m-1-10.972A4.5 4.5 0 0 0 21.028 15H10.973A4.5 4.5 0 0 0 7 11.028V10a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z");
}

</style>
