<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="em5pgnb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-32-filled" /></template>
<style>
.em5pgnb6h {
  fill: currentColor;
  d: path("M5.374 7.113A4.25 4.25 0 0 1 9.47 4h13.06a4.25 4.25 0 0 1 4.096 3.113l3.22 11.588c.738 2.664-1.265 5.299-4.03 5.299H6.183c-2.765 0-4.768-2.635-4.028-5.299zM8 26a1 1 0 1 0 0 2h16.002a1 1 0 1 0 0-2z");
}

</style>
