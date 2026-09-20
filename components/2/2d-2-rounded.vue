<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4ywebam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:2d-2-rounded" /></template>
<style>
.nv4ywebam {
  fill: currentColor;
  d: path("M10.073 16.217H5.838q-.16 0-.257-.098t-.098-.257v-.454q0-.067.018-.138t.086-.126q.967-.736 1.67-1.356t1.235-1.276q.477-.589.735-1.119t.258-1.126q0-.826-.454-1.331T7.939 8.43q-.56 0-.96.353q-.398.353-.54.876q-.06.17-.234.248t-.345.004q-.216-.08-.281-.3q-.065-.221.008-.456q.196-.762.906-1.2t1.465-.437q1.19 0 1.841.656t.651 1.798q0 .868-.34 1.629q-.34.762-.89 1.429q-.518.66-1.173 1.224t-1.264 1.037l.011.018h3.298q.196 0 .316.129q.119.128.119.325q0 .196-.129.325q-.129.128-.325.128m2.877-.005q-.348 0-.578-.23t-.23-.578v-6.89q0-.348.23-.578t.578-.23h2.042q1.887 0 2.876 1.155t.99 3.1t-.993 3.098t-2.873 1.153zm.17-.954h1.85q1.457 0 2.187-.89q.73-.891.73-2.406t-.73-2.409t-2.188-.894h-1.85z");
}

</style>
