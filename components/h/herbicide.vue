<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ki5990xzr"/><path class="zyjg0j66q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:herbicide" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki5990xzr {
  d: path("M12.184 21.5H4.5V13q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218q.104-.105.218-.198t.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071t.291-.044T7.5 10h5q.147 0 .294.014t.291.044q.145.028.286.071t.277.099t.266.126t.253.152q.122.081.236.175t.218.198q.105.104.198.218t.175.236t.152.253t.126.266t.099.277t.071.286t.044.291q.014.147.014.294v.716");
}

.zyjg0j66q {
  d: path("M7.5 10V4.5a2 2 0 0 1 2-2H17v4h-5.5V10m1.25-3.5l1.75 2m.5 13c0-4.5 2-6.5 6.5-6.5c0 4.5-2 6.5-6.5 6.5m0 0l3.5-3.5");
}

</style>
