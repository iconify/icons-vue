<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnllxr2mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-outline-sharp" /></template>
<style>
.xnllxr2mu {
  fill: currentColor;
  d: path("M1 18q.25-2.625 1.6-4.775t3.475-3.5L4.15 6.5q-.225-.35-.112-.75t.462-.6q.35-.225.75-.125t.6.45l2 3.325q.95-.4 1.988-.6T12 8t2.163.2t1.987.6l2-3.325q.2-.35.6-.45t.75.125q.35.2.45.6t-.1.75l-1.925 3.225q2.125 1.35 3.475 3.5T23 18zm17.013-3.787q.037-.438-.238-.863t-.675-.55t-.725.1t-.375.65t.225.85t.688.563t.737-.088t.363-.663M7.1 14.95q.4-.125.675-.55t.238-.862t-.363-.663t-.737-.088t-.688.563T6 14.2t.375.65t.725.1");
}

</style>
