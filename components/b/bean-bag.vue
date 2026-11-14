<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1jq9lben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bean-bag" /></template>
<style>
.u1jq9lben {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.441 21.5q-2.521-.031-3.257-2.64q-.649-2.301.64-4.687l.195-.457q3.59-8.411 6.858-8.956q.166-.027.328.019t.289.157q1.506 1.317 3.012 0q.127-.111.289-.157t.328-.019q3.268.545 6.858 8.956l.195.457q1.289 2.386.64 4.687q-.736 2.609-3.257 2.64q-6.559 1-13.118 0m9.28-.794q2.209-7.732-2.085-14.603q-.039-.063-.09-.117t-.111-.097t-.127-.073t-.139-.047t-.146-.019t-.147.01t-.142.039t-.131.065q-.063.039-.117.09t-.097.111t-.073.127t-.047.139t-.019.146t.01.147t.039.142t.065.131q3.941 6.306 1.915 13.397q-.02.071-.026.145q-.007.073.002.147q.008.073.031.143q.023.071.058.135t.084.121t.106.102t.123.08t.137.054q.143.041.292.024q.148-.017.278-.089q.131-.073.223-.19q.093-.117.134-.26");
}

</style>
