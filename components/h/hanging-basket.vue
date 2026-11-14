<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o31-2p3ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hanging-basket" /></template>
<style>
.o31-2p3ij {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 5.674V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.174l-7.261 6.777l-.001.001q-.109.101-.171.237q-.061.136-.067.285v.027q0 3.935 2.47 6.404Q8.564 21.75 12 21.75t5.78-2.345q2.47-2.469 2.47-6.405v-.026q-.006-.149-.067-.285t-.171-.237l-.001-.001zM9.438 12.25H6.403l3.439-3.21Q9.25 9.724 9.25 11q0 .719.188 1.25m5.124 0q.188-.531.188-1.25q0-1.276-.592-1.96l3.439 3.21zm-.707-3.492Q13.182 8.25 12 8.25t-1.855.508L12 7.026z");
}

</style>
