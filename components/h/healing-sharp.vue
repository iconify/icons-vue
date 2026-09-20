<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvd0cpbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:healing-sharp" /></template>
<style>
.zvd0cpbmh {
  fill: currentColor;
  d: path("M6.85 21.416L2.566 17.13L17.112 2.585l4.284 4.284zm5.696-4.604l4.246-4.246l4.604 4.603l-4.246 4.247zm.032-2.622q.23-.233.23-.578t-.233-.574t-.578-.23t-.575.233t-.23.578t.234.574t.577.23t.575-.233m-2.19-1.382q.345 0 .575-.233t.23-.578t-.234-.575t-.578-.23t-.574.234t-.23.577t.233.575t.578.23m3.23 0q.346 0 .575-.233t.23-.578q0-.345-.233-.575t-.578-.23t-.574.234t-.23.577t.233.575t.578.23M7.183 11.41l-4.58-4.58L6.85 2.586l4.585 4.584zm5.395-.451q.23-.233.23-.578t-.233-.574t-.578-.23t-.575.233t-.23.578t.234.575t.577.23t.575-.234");
}

</style>
