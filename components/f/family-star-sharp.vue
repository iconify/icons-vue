<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0zhdc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-star-sharp" /></template>
<style>
.wy0zhdc5q {
  fill: currentColor;
  d: path("M13.801 14.845q.793-.616 1.16-1.549H9.04q.367.933 1.16 1.55q.793.615 1.801.615t1.801-.616m-3.123-3.244q.322-.322.322-.793t-.322-.793q-.322-.323-.793-.323t-.794.322q-.322.323-.322.794q0 .47.322.793q.322.322.793.322t.794-.322m4.23 0q.323-.322.323-.793t-.322-.793q-.323-.323-.794-.323q-.47 0-.793.323q-.322.322-.322.793q0 .47.322.793q.322.322.794.322q.47 0 .793-.322M8.125 7.092L12 1.937l3.875 5.155l6.139 2.07l-3.941 5.336l.156 6.056L12 18.733l-6.229 1.82l.156-6.08l-3.915-5.312z");
}

</style>
