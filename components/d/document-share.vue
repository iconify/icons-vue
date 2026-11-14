<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jup3onb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:document-share" /></template>
<style>
.jup3onb7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 2.555Q1.75 3.361 1.75 4.5v15q0 2.75 2.75 2.75h6q2.75 0 2.75-2.75V6q0-.149-.057-.287t-.163-.243l-3.5-3.5q-.105-.106-.243-.163T9 1.75H4.5q-1.139 0-1.945.805M20 4.25q-2.25 0-2.25 2.25q0 .97.418 1.521l-1.173 1.76q-.232-.031-.495-.031q-2.25 0-2.25 2.25t2.25 2.25q.263 0 .495-.031l1.173 1.76q-.418.551-.418 1.521q0 2.25 2.25 2.25t2.25-2.25T20 15.25q-.263 0-.495.031l-1.173-1.76q.418-.551.418-1.521t-.418-1.521l1.173-1.76q.232.031.495.031q2.25 0 2.25-2.25T20 4.25");
}

</style>
