<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytromvbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anti-static-mat" /></template>
<style>
.ytromvbal {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.726 3.75h11.276q1.301 0 2.047 1.066t.302 2.288l-2.727 7.5q-.599 1.646-2.35 1.646h-3.399q.398 1.129 2.057 1.865q2.726 1.209 3.289 3.179q.02.071.026.145q.007.073-.002.147q-.008.073-.031.143q-.023.071-.058.135t-.084.121q-.048.056-.106.102t-.123.08t-.137.054t-.145.026t-.147-.002t-.143-.031q-.071-.023-.135-.058t-.121-.084q-.056-.048-.102-.106t-.08-.123t-.054-.137q-.37-1.295-2.455-2.22q-2.618-1.162-3.006-3.236h-6.32q-1.301 0-2.047-1.066t-.302-2.288l2.727-7.5q.599-1.646 2.35-1.646m5.524 5q0 2.25 2.25 2.25t2.25-2.25T15.5 6.5t-2.25 2.25");
}

</style>
