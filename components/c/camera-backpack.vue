<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj4brnbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-backpack" /></template>
<style>
.wj4brnbdj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.993 6.507q-1.213-1.212-2.772-1.588Q14.945 2.25 12 2.25T8.779 4.919q-1.559.376-2.772 1.588q-1.074 1.074-1.491 2.42q.101-.086.226-.131T5 8.75h14q.133 0 .258.046q.125.045.226.131q-.417-1.346-1.491-2.42M12 3.75q1.323 0 1.646 1h-3.292q.323-1 1.646-1m-7.75 7q0-.484.067-.941q.044.099.115.181t.161.14q.091.059.195.089q.104.031.212.031h14q.108 0 .212-.031q.104-.03.195-.089q.09-.058.161-.14t.115-.181q.067.457.067.941v5.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-3.5q-2.485 0-4.243-1.757Q4.25 18.735 4.25 16.25zm4 4.75q0 3.75 3.75 3.75t3.75-3.75T12 11.75T8.25 15.5");
}

</style>
