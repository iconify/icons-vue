<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juhyh1bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emergency-home-rounded" /></template>
<style>
.juhyh1bud {
  fill: currentColor;
  d: path("M11.401 20.654q-.295-.121-.537-.358l-7.16-7.16q-.237-.242-.358-.537T3.225 12t.121-.602t.358-.534l7.16-7.16q.242-.242.537-.36t.599-.12t.602.118t.535.36l7.16 7.16q.241.237.36.535q.118.298.118.602t-.118.599t-.36.538l-7.16 7.16q-.237.236-.535.357t-.602.121t-.599-.121m.956-7.624q.143-.143.143-.357v-4.23q0-.214-.143-.358T12 7.943t-.357.144t-.143.356v4.231q0 .213.143.357t.357.143t.357-.143m.077 2.192q.182-.182.182-.434t-.182-.433t-.434-.182t-.434.182t-.182.433t.182.434q.182.182.434.182t.434-.182");
}

</style>
