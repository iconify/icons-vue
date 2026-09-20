<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uymqj-bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-5-4-outline-sharp" /></template>
<style>
.uymqj-bpz {
  fill: currentColor;
  d: path("M3 20V4h18v16zm2-2h14V6H5zm0 0V6z");
}

</style>
