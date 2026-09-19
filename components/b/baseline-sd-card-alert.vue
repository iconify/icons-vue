<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7v69bc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-sd-card-alert" /></template>
<style>
.n7v69bc8x {
  fill: currentColor;
  d: path("M18 2h-8L4.02 8L4 20c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-5 15h-2v-2h2zm0-4h-2V8h2z");
}

</style>
