<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2np755g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-capslock-badge-sharp" /></template>
<style>
.pr2np755g {
  fill: currentColor;
  d: path("M7 17h10v-2H7zm1.4-4L12 9.4l3.6 3.6l1.4-1.4l-5-5l-5 5zM3 21V3h18v18z");
}

</style>
