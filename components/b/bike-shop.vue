<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo55ovms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-shop" /></template>
<style>
.fgo55ovms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022zM11.25 17.5q0-1.833-.896-2.77l.772-1.102l2.018 1.835q-.394.821-.394 2.037q0 3.75 3.75 3.75t3.75-3.75t-3.75-3.75q-1.476 0-2.371.581L12.94 13.25H14q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 11.75h-3q-.027 0-.053.002q-.084.006-.164.03t-.153.066q-.073.041-.135.097q-.061.056-.109.125h-.001l-1.322 1.889q-.677-.209-1.563-.209q-1.553 0-2.652 1.098Q3.75 15.947 3.75 17.5q0 3.75 3.75 3.75t3.75-3.75");
}

</style>
