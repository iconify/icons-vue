<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8zm44cqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-label" /></template>
<style>
.a8zm44cqz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.125 1.75h9.75q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375H12.75v2.302q.128.048.256.112l2.5 1.25q.294.147.518.336q-.19-.006-.359.079L12 16.161l-3.665-1.832q-.169-.085-.359-.079q.224-.189.518-.336l2.5-1.25q.128-.064.256-.112V10.25H7.125q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375m9.21 13.921q.115-.057.204-.149t.142-.208q.069.285.069.613v2.646q0 1.391-1.244 2.013l-2.5 1.25q-.229.115-.459.177q.098-.104.15-.237q.053-.133.053-.276v-4.036zm-5.085 1.793l-3.585-1.793q-.115-.057-.204-.149t-.142-.208q-.069.285-.069.613v2.646q0 1.391 1.244 2.013l2.499 1.25q.23.115.46.177q-.098-.104-.15-.237q-.053-.133-.053-.276z");
}

</style>
