<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="stz6wfwcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-3-28-regular" /></template>
<style>
.stz6wfwcf {
  fill: currentColor;
  d: path("M2 5.75A.75.75 0 0 1 2.75 5h22.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 5.75m0 16a.75.75 0 0 1 .75-.75h22.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75M2.75 13a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5z");
}

</style>
