<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwn674mhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-airlines" /></template>
<style>
.zwn674mhx {
  fill: currentColor;
  d: path("M13 4L2 20h17l3-16zm1.5 10a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
