<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xntaenbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-off-rounded" /></template>
<style>
.xntaenbaq {
  fill: currentColor;
  d: path("M19.075 21.9L17.15 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l2 2H3.15L2.075 4.925q-.3-.3-.3-.712t.3-.713t.713-.3t.712.3l17 17q.3.3.3.7t-.3.7t-.712.3t-.713-.3m1.75-4.163q-.275-.037-.525-.287l-5.925-5.925L19.6 8.25q.35-.225.4-.562t-.125-.613t-.5-.375t-.675.125L13.15 10.3l-4.6-4.6q-.25-.25-.288-.525t.088-.55t.35-.45T9.275 4H20q.825 0 1.413.588T22 6v10.725q0 .35-.175.575t-.45.35t-.55.088");
}

</style>
