<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3rvt5biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flashlight-off-outline" /></template>
<style>
.c3rvt5biw {
  fill: currentColor;
  d: path("M19.8 22.6L16 18.8V22H8V10.8L1.4 4.2l1.4-1.4l18.4 18.4zM10 20h4v-3.2l-4-4zm6-6.85l-2-2v-.75l2-3V7H9.85l-2-2H16V4H6.85L6 3.15V2h12v6l-2 3zm-3.575-3.575");
}

</style>
