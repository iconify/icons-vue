<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdy_l4k_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:live-tv" /></template>
<style>
.sdy_l4k_a {
  fill: currentColor;
  d: path("M21 6h-7.59l3.29-3.29L16 2l-4 4l-4-4l-.71.71L10.59 6H3a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V8a2 2 0 0 0-2-2m0 14H3V8h18zM9 10v8l7-4z");
}

</style>
