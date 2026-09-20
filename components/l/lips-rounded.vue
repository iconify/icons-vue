<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-te3312z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lips-rounded" /></template>
<style>
.s-te3312z {
  fill: currentColor;
  d: path("M11.967 12.558q-2.273 0-4.458-.5t-4.34-1.162q-.261-.08-.32-.336q-.059-.254.147-.44L6.723 6.7q.348-.31.767-.48t.877-.17q.33 0 .651.09q.322.089.62.262l1.947 1.185q.192.136.424.136q.233 0 .426-.136L14.4 6.402q.298-.173.61-.262q.313-.09.642-.09q.46 0 .888.17q.427.17.776.48l3.67 3.402q.206.187.141.441q-.065.255-.327.342q-2.18.673-4.36 1.173t-4.473.5M11.677 18q-3.048 0-5.37-1.484t-3.673-4.035q-.13-.242.056-.466q.187-.225.46-.119q2.158.731 4.353 1.187t4.459.456q2.307 0 4.522-.474q2.214-.474 4.391-1.211q.292-.106.482.109t.059.481q-1.287 2.539-3.711 4.047Q15.28 18 12.342 18z");
}

</style>
