<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s4p8mbb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-12-regular" /></template>
<style>
.s4p8mbb0x {
  fill: currentColor;
  d: path("M10 7.5a.5.5 0 0 0 1 0v-6a.5.5 0 0 0-.5-.5H4.47a.5.5 0 0 0 0 1h4.823L7.146 4.146a.5.5 0 1 0 .708.708L10 2.707zM6.354 6.354a.5.5 0 1 0-.708-.708l-1.5 1.5a.5.5 0 1 0 .708.708zm-3 3a.5.5 0 1 0-.708-.708l-1.5 1.5a.5.5 0 0 0 .708.708z");
}

</style>
