<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utk51fb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:coin-stack-20-filled" /></template>
<style>
.utk51fb6q {
  fill: currentColor;
  d: path("M16 6c0 2.21-2.686 4-6 4S4 8.21 4 6s2.686-4 6-4s6 1.79 6 4m-.25 2.853C14.485 10.15 12.38 11 10 11s-4.485-.85-5.75-2.147C4.088 9.216 4 9.6 4 10c0 2.21 2.686 4 6 4s6-1.79 6-4a2.8 2.8 0 0 0-.25-1.147m0 4C14.485 14.15 12.38 15 10 15s-4.485-.85-5.75-2.147C4.088 13.216 4 13.6 4 14c0 2.21 2.686 4 6 4s6-1.79 6-4a2.8 2.8 0 0 0-.25-1.147");
}

</style>
