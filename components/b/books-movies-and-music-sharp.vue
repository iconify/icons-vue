<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb8m9pbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:books-movies-and-music-sharp" /></template>
<style>
.cb8m9pbzt {
  fill: currentColor;
  d: path("M4 21V7.135l9.846-3.031V7H16v3.712q-2.29.25-3.799 1.941t-1.509 4q0 1.253.493 2.38q.492 1.127 1.382 1.967zM7.692 7h5.154V5.489zm6.165 12.49q-1.165-1.165-1.165-2.836t1.165-2.836t2.835-1.164t2.836 1.164t1.164 2.836t-1.164 2.835t-2.836 1.165q-1.67 0-2.835-1.165m1.97-.95l2.73-1.924l-2.73-1.923z");
}

</style>
