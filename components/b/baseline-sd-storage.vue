<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmlyllb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-sd-storage" /></template>
<style>
.rmlyllb7l {
  fill: currentColor;
  d: path("M18 2h-8L4.02 8L4 20c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-6 6h-2V4h2zm3 0h-2V4h2zm3 0h-2V4h2z");
}

</style>
