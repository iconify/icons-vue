<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwf7z6blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-home-outline" /></template>
<style>
.bwf7z6blm {
  fill: currentColor;
  d: path("M17.616 18.885h.769v-2.5h2.5v-.77h-2.5v-2.5h-.77v2.5h-2.5v.77h2.5zM18 20q-1.671 0-2.835-1.164Q14 17.67 14 16t1.165-2.835T18 12t2.836 1.165T22 16t-1.164 2.836T18 20M5 18V7.5l7-5.288L19 7.5v1.82q-.244-.055-.492-.072T18 9.231V8l-6-4.538L6 8v9h5.306q.032.263.095.513t.159.487zm7-7.77");
}

</style>
