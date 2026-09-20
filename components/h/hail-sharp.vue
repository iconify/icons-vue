<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhppk8b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hail-sharp" /></template>
<style>
.hhppk8b8e {
  fill: currentColor;
  d: path("M4.885 21.5v-5h2v5zm4.923 0V8.85q-1.558.425-2.327 1.495t-.942 2.77h-1q.173-2.738 1.884-4.215T12 7.423q2.616 0 4-.853q1.385-.853 1.5-3.378h1q-.058 2.124-1.12 3.419t-3.188 1.597V21.5h-1v-5.884h-2.384V21.5zM12 5.77q-.71 0-1.201-.492t-.491-1.201t.491-1.201T12 2.385t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491");
}

</style>
