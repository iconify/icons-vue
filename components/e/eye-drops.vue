<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8kyi2yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-drops" /></template>
<style>
.zc8kyi2yb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 8.804V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 1.75 10 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v6.304q-1.491.219-2.609 1.337Q5.25 11.532 5.25 13.5V17q0 1.968 1.391 3.359T10 21.75t3.359-1.391T14.75 17v-3.5q0-1.968-1.391-3.359q-1.118-1.118-2.609-1.337m6.643-2.245q.07-.096.166-.166q.06-.043.127-.074t.139-.048t.145-.02q.074-.003.147.008q.073.012.142.037q.07.026.133.064t.117.089t.098.11q2.143 2.947 2.143 4.691Q20.75 14 18 14t-2.75-2.75q0-1.744 2.143-4.691");
}

</style>
