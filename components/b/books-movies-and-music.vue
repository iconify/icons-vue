<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhir0zwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:books-movies-and-music" /></template>
<style>
.wmhir0zwc {
  fill: currentColor;
  d: path("M4.77 21q-.31 0-.54-.23T4 20.23V7.82q0-.293.146-.533q.146-.239.427-.325l8.366-2.577q.346-.104.627.115q.28.22.28.577V7h1.385q.31 0 .54.23t.229.54v2.942q-2.29.25-3.799 1.941t-1.509 4q0 1.253.493 2.38q.492 1.127 1.382 1.967zM7.691 7h5.154V5.489zm6.165 12.49q-1.165-1.165-1.165-2.836t1.165-2.836t2.835-1.164t2.836 1.164t1.164 2.836t-1.164 2.835t-2.836 1.165q-1.67 0-2.835-1.165m1.97-.95l2.73-1.924l-2.73-1.923z");
}

</style>
