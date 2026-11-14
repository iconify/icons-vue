<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_vzqcbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cricket-ground-top" /></template>
<style>
.e_vzqcbjq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.818 6.108Q1.75 8.53 1.75 12t3.068 5.892Q7.805 20.25 12 20.25t7.182-2.358Q22.25 15.47 22.25 12t-3.068-5.892Q16.195 3.75 12 3.75T4.818 6.108M12 6.75q2.25 0 2.25 2.25v6q0 2.25-2.25 2.25T9.75 15V9q0-2.25 2.25-2.25");
}

</style>
