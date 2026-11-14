<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3ohuxm5f"/><path class="o8cqgnbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:failback" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8cqgnbov {
  d: path("m17.5 15.5l-2 2l2 2");
}

.y3ohuxm5f {
  d: path("M6 2.5h10a3 3 0 0 1 3 3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3a3 3 0 0 1 3-3m6.684 14.75H6q-.147 0-.294-.014t-.291-.044q-.145-.028-.286-.071t-.277-.099q-.136-.057-.266-.126q-.13-.07-.253-.152q-.122-.081-.236-.175t-.218-.198t-.198-.218t-.175-.236t-.152-.253t-.126-.266t-.099-.277t-.071-.286t-.044-.291Q3 14.397 3 14.25t.014-.294t.044-.291q.028-.145.071-.286t.099-.277t.126-.266t.152-.253t.175-.236t.198-.218t.218-.198t.236-.175t.253-.152t.266-.126t.277-.099t.286-.071q.144-.029.291-.044T6 11.25h10q.215 0 .427.031q.213.03.419.091q.206.06.402.15q.195.089.376.205q.18.117.342.257t.303.304q.141.162.257.343t.205.376M6.5 5.5h.01m-.01 8.75h.01m8.99 3.25h4a2 2 0 0 1 0 4h-3");
}

</style>
