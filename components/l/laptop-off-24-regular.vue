<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onj7ckbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-off-24-regular" /></template>
<style>
.onj7ckbpy {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06L17.94 19H2.75a.75.75 0 0 1 0-1.5h13.69l-1.5-1.5H6.25A2.25 2.25 0 0 1 4 13.75v-7.5c0-.347.08-.675.22-.969l-2-2a.75.75 0 0 1 0-1.061M17.75 4A2.25 2.25 0 0 1 20 6.25v7.5c0 .832-.452 1.556-1.123 1.945L17.682 14.5h.068a.75.75 0 0 0 .75-.75v-7.5a.75.75 0 0 0-.75-.75H8.682L7.182 4zM5.5 13.75c0 .414.336.75.75.75h7.19L5.5 6.56z");
}

</style>
