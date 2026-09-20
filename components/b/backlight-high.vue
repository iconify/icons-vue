<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkw4ugbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:backlight-high" /></template>
<style>
.zkw4ugbqd {
  fill: currentColor;
  d: path("M1 15v-2h4v2zm5.35-5.25L3.525 6.925l1.4-1.425L7.75 8.35zM7 18v-3h10v3zm4-11V2h2v5zm6.65 2.75l-1.4-1.4l2.825-2.825l1.425 1.4zM19 15v-2h4v2z");
}

</style>
