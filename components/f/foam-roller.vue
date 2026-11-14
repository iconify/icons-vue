<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5p-rb02n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:foam-roller" /></template>
<style>
.j5p-rb02n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.949 7.029Q1.75 9.107 1.75 12t1.199 4.971Q4.264 19.25 6.25 19.25H18q1.898 0 3.135-2.298Q22.25 14.881 22.25 12t-1.115-4.952Q19.898 4.75 18 4.75H6.248q-1.985.001-3.299 2.279M9.031 17.75q.272-.349.52-.779Q10.75 14.893 10.75 12T9.551 7.029q-.248-.43-.52-.779H18q1.002 0 1.815 1.509q.935 1.738.935 4.241t-.935 4.241Q19.002 17.75 18 17.75zM4.5 12q0-3.25 1.75-3.25T8 12t-1.75 3.25T4.5 12");
}

</style>
