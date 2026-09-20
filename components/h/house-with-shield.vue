<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dulnyxb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:house-with-shield" /></template>
<style>
.dulnyxb_t {
  fill: currentColor;
  d: path("M12 18q1.725-.425 2.863-1.987T16 12.55V10l-4-2l-4 2v2.55q0 1.9 1.138 3.463T12 18m-8 3V9l8-6l8 6v12z");
}

</style>
