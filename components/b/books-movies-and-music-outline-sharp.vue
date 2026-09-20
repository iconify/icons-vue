<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyzxusb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:books-movies-and-music-outline-sharp" /></template>
<style>
.iyzxusb_h {
  fill: currentColor;
  d: path("M3 22V6.25l12-4.8V6h2v4h-2V8H5v12h5.175l2 2zM9 6h4V4.45zm4.463 14.538Q12 19.075 12 17t1.463-3.537T17 12t3.538 1.463T22 17t-1.463 3.538T17 22t-3.537-1.463M15.75 19.5l4-2.5l-4-2.5zM5 20V8z");
}

</style>
