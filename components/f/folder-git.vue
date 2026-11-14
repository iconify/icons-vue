<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s55dflb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-git" /></template>
<style>
.s55dflb9y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v3.488q-.575-.239-1.25-.239q-1.198 0-2.083.753Q17.709 11.5 15.5 11.5q-3.25 0-3.25 3.25q0 2.016 1.25 2.781v.188q-1.002.614-1.201 2.031H5q-2.75 0-2.75-2.75zm13.25 5.75q-2 0-2 2q0 1.581 1.25 1.912v1.926q-1.25.331-1.25 1.912q0 2 2 2t2-2q0-.269-.036-.501q2.627-.601 3.431-2.534q.579-.109 1.02-.55q.586-.587.585-1.416q.001-.827-.585-1.414q-.586-.586-1.415-.586t-1.415.586t-.585 1.414v.002q0 .828.585 1.414q.117.117.244.211q-.756 1.211-2.871 1.529q-.099-.039-.208-.067v-1.926q1.25-.331 1.25-1.912q0-2-2-2");
}

</style>
