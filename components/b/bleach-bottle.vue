<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlc7r_bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bleach-bottle" /></template>
<style>
.qlc7r_bjh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 2.75h1q2.25 0 2.25 2.25v1q0 .413-.076.75h1.576V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h3.5q2.25 0 2.25 2.25v1.379q.5.56.5 1.621v11q0 2.25-2.25 2.25H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V10q0-.167.071-.318t.199-.258l2.202-1.835Q6.25 7.03 6.25 6V5q0-2.25 2.25-2.25m9.75 4.007V6q0-.75-.75-.75h-2.75v1.5H18q.129 0 .25.007m-5.681 3.755q-.037-.044-.081-.081q-.056-.049-.12-.085q-.065-.036-.135-.059t-.144-.032q-.073-.008-.147-.003q-.073.006-.144.026t-.137.053t-.124.079t-.106.102Q8.5 13.931 8.5 16q0 3.5 3.5 3.5t3.5-3.5q0-2.069-2.931-5.488");
}

</style>
