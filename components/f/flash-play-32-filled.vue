<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l_jfolbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-play-32-filled" /></template>
<style>
.l_jfolbru {
  fill: currentColor;
  d: path("M12 2a2 2 0 0 0-1.897 1.368l-4 12A2 2 0 0 0 8 18h2.415l-2.288 8.825c-.67 2.587 2.64 4.28 4.345 2.222l2.193-2.646a9 9 0 0 1 10.127-12.223l.748-.902A2 2 0 0 0 24 10h-3.114l1.987-5.298A2 2 0 0 0 21 2zm18.5 21a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0M21 26.058a.5.5 0 0 0 .777.416l4.598-3.062a.5.5 0 0 0 0-.833l-4.598-3.062a.5.5 0 0 0-.777.417z");
}

</style>
