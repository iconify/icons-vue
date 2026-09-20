<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s7a2wxbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-up-20-regular" /></template>
<style>
.s7a2wxbfp {
  fill: currentColor;
  d: path("M5.854 3.146a.5.5 0 1 0-.708.708l4.5 4.5a.5.5 0 0 0 .708 0l4.5-4.5a.5.5 0 0 0-.708-.708L10 7.293zm9 13l-4.5-4.5a.5.5 0 0 0-.708 0l-4.5 4.5a.5.5 0 0 0 .708.708L10 12.707l4.146 4.147a.5.5 0 0 0 .708-.708");
}

</style>
