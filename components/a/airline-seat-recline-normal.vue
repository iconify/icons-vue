<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1ltygbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-recline-normal" /></template>
<style>
.z1ltygbns {
  fill: currentColor;
  d: path("M14.75 19H8.366q-.691 0-1.153-.462t-.463-1.154V7h1v10.385q0 .23.192.423t.423.192h6.385zm-4-12.5q-.71 0-1.201-.491q-.491-.492-.491-1.201t.491-1.201q.492-.491 1.201-.491t1.201.49q.491.492.491 1.202t-.491 1.2t-1.201.492m5.5 15V17h-6q-.633 0-1.066-.434q-.434-.433-.434-1.066V9.73q0-.857.571-1.428t1.429-.571t1.429.571t.571 1.429V15h3q.633 0 1.066.434q.434.433.434 1.066v5z");
}

</style>
