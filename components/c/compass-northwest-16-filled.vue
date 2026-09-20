<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="azijqzbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:compass-northwest-16-filled" /></template>
<style>
.azijqzbtt {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1M5.81 4.83a.75.75 0 0 0-.978.979l1.045 2.543c.33.802.969 1.44 1.771 1.77l2.542 1.045a.75.75 0 0 0 .978-.979l-1.044-2.542a3.25 3.25 0 0 0-1.77-1.771z");
}

</style>
