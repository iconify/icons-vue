<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sp_qrdb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bunpo" /></template>
<style>
.sp_qrdb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.621 22.944c3.746 4.504 2.494 11.49-1.494 15.49c-7.492 6.986-14.984 4.745-13.49-4.999q2.252-16.477 14.984-26.97c4.493-2.987 7.492 1.506 3 5.999c-11.239 11.238-20.225 11.238-31.463 1.494");
}

</style>
