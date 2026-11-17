<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtz2t2nmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplets-fill" /></template>
<style>
.rtz2t2nmk {
  fill: currentColor;
  d: path("M18.581 2.186c.188.134.365.281.54.431c.924.792 1.758 1.736 2.305 2.83c.352.704.574 1.476.574 2.267a4 4 0 0 1-7.685 1.558c-.84-1.987.108-4.024 1.432-5.538q.527-.6 1.133-1.118q.26-.227.539-.43a1 1 0 0 1 1.162 0m-10 5.143c.296.212.577.445.853.681a18 18 0 0 1 1.82 1.798C12.753 11.521 13.999 13.662 14 16a6 6 0 0 1-6 6a5.97 5.97 0 0 1-4.243-1.757A5.98 5.98 0 0 1 2 16c0-1.215.346-2.401.887-3.483c.863-1.727 2.221-3.257 3.681-4.508c.275-.236.555-.469.851-.68a1 1 0 0 1 1.162 0");
}

</style>
