<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mulpmd7os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:communal-bin" /></template>
<style>
.mulpmd7os {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.349 3.628l-2 3.5q-.099.173-.099.372q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 8.25h1.132q-.254.571-.186 1.249l.65 6.5q.107 1.069.673 1.631q-.519.675-.519 1.87q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h3.876q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-1.195-.519-1.87q.566-.562.673-1.631l.65-6.5q.068-.678-.186-1.249H21q.199 0 .372-.099q.13-.074.221-.192t.131-.262t.02-.292q-.019-.148-.093-.277l-2-3.5q-.049-.086-.119-.157q-.07-.07-.156-.12t-.181-.075T19 3.25H5q-.099 0-.195.026t-.181.075q-.086.05-.156.12q-.07.071-.119.157");
}

</style>
