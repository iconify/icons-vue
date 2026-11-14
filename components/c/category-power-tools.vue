<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6p41c9pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-power-tools" /></template>
<style>
.o6p41c9pv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 3.75h6q3.75 0 3.75 3.75q0 3.539-3.34 3.738q.34.711.34 1.762v1.5q0 1.045-.336 1.754q1.137.055 1.957.875q.879.878.879 2.121q0 3-3 3h-5.5q-3 0-3-3q0-2.916 2.835-2.998q-.335-.708-.335-1.752V13q0-1.042.334-1.75H11q-2.222 0-3.128-1.317q-.527.317-1.372.317q-2.121 0-2.243-2H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 7.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.757q.122-2 2.243-2q.991 0 1.545.436q.14-.174.303-.338Q9.447 3.75 11 3.75");
}

</style>
