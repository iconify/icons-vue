<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2idmd51c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-right-24-filled" /></template>
<style>
.l2idmd51c {
  fill: currentColor;
  d: path("M11 21a1 1 0 0 1 0-2h6.586L3.293 4.707a1 1 0 0 1 1.414-1.414L19 17.586V11a1 1 0 1 1 2 0v9a1 1 0 0 1-1 1z");
}

</style>
