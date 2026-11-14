<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q94dagbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-link" /></template>
<style>
.q94dagbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5H7a4 4 0 0 0 0 8h1.5m5-8H15q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132t.355.168t.336.202q.164.109.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388Q19 8.303 19 8.5q0 .149-.011.297q-.011.149-.033.296t-.055.292t-.077.287q-.043.143-.097.281t-.119.273t-.138.264t-.157.252t-.176.24t-.193.226t-.209.211q-.109.102-.225.195t-.238.178t-.251.16t-.262.141t-.272.12M8 8.5h6m2.5 6.5v6.5m3-6.5v6.5m-4.75-4.75h6.5m-6.5 3h6.5");
}

</style>
