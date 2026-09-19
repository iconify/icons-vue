<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft930ccsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:brightness-3" /></template>
<style>
.ft930ccsa {
  fill: currentColor;
  d: path("M9 2c-1.05 0-2.05.16-3 .46c4.06 1.27 7 5.06 7 9.54s-2.94 8.27-7 9.54c.95.3 1.95.46 3 .46c5.52 0 10-4.48 10-10S14.52 2 9 2");
}

</style>
