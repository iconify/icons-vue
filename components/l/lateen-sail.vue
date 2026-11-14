<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or2-zsbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lateen-sail" /></template>
<style>
.or2-zsbkb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.403 11.165l8.462-6.006q1.263-.896 2.552-.036q1.288.86.944 2.37l-1.365 6.005q-.397 1.751-2.193 1.752H12.75v1.5H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .24-.14.436l-2.5 3.5q-.052.073-.119.131q-.068.059-.148.1t-.166.062t-.177.021h-13q-.09 0-.177-.021t-.166-.062t-.148-.1q-.067-.058-.119-.131l-2.5-3.5q-.087-.121-.121-.267q-.033-.145-.009-.292q.025-.147.104-.274t.2-.213q.196-.14.436-.14h8.25v-1.5H8.705q-1.644-.001-2.143-1.567t.841-2.517z");
}

</style>
