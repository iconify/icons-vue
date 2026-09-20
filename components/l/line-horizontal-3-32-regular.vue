<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-unscfsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-3-32-regular" /></template>
<style>
.z-unscfsl {
  fill: currentColor;
  d: path("M2 6a1 1 0 0 1 1-1h26a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m0 10a1 1 0 0 1 1-1h26a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1 9a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2z");
}

</style>
