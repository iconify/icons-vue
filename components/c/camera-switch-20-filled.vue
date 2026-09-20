<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nm0b_mdcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:camera-switch-20-filled" /></template>
<style>
.nm0b_mdcl {
  fill: currentColor;
  d: path("M14.146 2.146a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L15.293 5H4a1 1 0 0 0-1 1v6.5a.5.5 0 0 1-1 0V6a2 2 0 0 1 2-2h11.293l-1.147-1.146a.5.5 0 0 1 0-.708M17 14a1 1 0 0 1-1 1H4.707l1.147-1.146a.5.5 0 0 0-.708-.708l-2 2a.5.5 0 0 0 0 .708l2 2a.5.5 0 0 0 .708-.708L4.707 16H16a2 2 0 0 0 2-2V7.5a.5.5 0 0 0-1 0zm-4-4a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

</style>
