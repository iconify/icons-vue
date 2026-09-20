<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjedr8bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-recline-normal-sharp" /></template>
<style>
.wjedr8bzz {
  fill: currentColor;
  d: path("M6.75 19V7h1v11h7v1zm4-12.5q-.71 0-1.201-.491q-.491-.492-.491-1.201t.491-1.201q.492-.491 1.201-.491t1.201.49q.491.492.491 1.202t-.491 1.2t-1.201.492m5.5 15V17h-7.5V9.73q0-.857.571-1.428t1.429-.571t1.429.571t.571 1.429V15h4.5v6.5z");
}

</style>
