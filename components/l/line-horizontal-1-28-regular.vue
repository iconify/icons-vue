<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="iecfkvboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-1-28-regular" /></template>
<style>
.iecfkvboc {
  fill: currentColor;
  d: path("M2 13.75a.75.75 0 0 1 .75-.75h22.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
