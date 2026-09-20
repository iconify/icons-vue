<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in2hs_b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-read-play-outline-sharp" /></template>
<style>
.in2hs_b8r {
  fill: currentColor;
  d: path("m10 14l6-4l-6-4zm-8 8V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
