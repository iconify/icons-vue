<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtp2v_b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-32-filled" /></template>
<style>
.vtp2v_b6p {
  fill: currentColor;
  d: path("M16 30c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14M14 9a1 1 0 1 1 2 0v7h4a1 1 0 1 1 0 2h-5a1 1 0 0 1-1-1z");
}

</style>
