<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge80sub5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-run-outline-sharp" /></template>
<style>
.ge80sub5z {
  fill: currentColor;
  d: path("M13.5 22.5v-5.673l-2.908-2.789l-1.077 4.785l-5.938-1.207l.207-.981l4.8.98l1.87-9.561L7.5 9.273V12.5h-1V8.608l3.989-1.662q.644-.26.95-.353T12 6.5q.39 0 .725.208t.552.561l1 1.6q.63 1.012 1.743 1.744t2.48.849v1q-1.4-.096-2.809-.88q-1.408-.784-2.441-2.447l-.889 4.519L14.5 15.73v6.77zM12.299 4.701q-.491-.492-.491-1.201t.491-1.201t1.201-.491t1.201.491q.491.492.491 1.201t-.491 1.201q-.492.491-1.201.491t-1.201-.491");
}

</style>
