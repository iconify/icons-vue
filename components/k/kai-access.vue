<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uid06s3yz"/><path class="t2ly_x11v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kai-access" /></template>
<style>
.t2ly_x11v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.03L6.563 33.37l9.187-20.76c.916-2.07 2.513-2.65 4.58-2.65h6.06l3.159 11.375m-5.483 8.706L12.411 38.04H4.5h0l39-20.917");
}

.uid06s3yz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.726 24.409l7.632-.157l3.83 13.788h-8.214l-1.908-8.002m-7.326-1.996l4.01-9.402h.606l1.48 6.21");
}

</style>
