<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my3cq462x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flex-direction" /></template>
<style>
.my3cq462x {
  fill: currentColor;
  d: path("M2 20v-7h9v7zm0-9V4h9v7zm2-2h5V6H4zm14 11l-5-5l1.4-1.4l2.6 2.575V4h2v12.175l2.6-2.575L23 15z");
}

</style>
