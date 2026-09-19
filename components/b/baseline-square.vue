<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6vc83tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-square" /></template>
<style>
.dk6vc83tr {
  fill: currentColor;
  d: path("M3 3h18v18H3z");
}

</style>
