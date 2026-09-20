<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8z74mkci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-flow-diagonal-up-right-24-filled" /></template>
<style>
.w8z74mkci {
  fill: currentColor;
  d: path("M19.78 5.28a.75.75 0 0 0-1.06-1.06l-9.472 9.47a4 4 0 1 0 1.06 1.06z");
}

</style>
