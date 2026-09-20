<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z-n1cp7xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-28-regular" /></template>
<style>
.z-n1cp7xm {
  fill: currentColor;
  d: path("M3 6.75A.75.75 0 0 1 3.75 6h18.5a.75.75 0 0 1 0 1.5H3.75A.75.75 0 0 1 3 6.75m0 14a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75M3.75 13a.75.75 0 0 0 0 1.5h20.5a.75.75 0 0 0 0-1.5z");
}

</style>
