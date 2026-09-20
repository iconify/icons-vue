<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm00qnbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:healing-outline-sharp" /></template>
<style>
.tm00qnbgx {
  fill: currentColor;
  d: path("m12 16.266l-5.15 5.15l-4.284-4.285l5.169-5.17l-5.131-5.13L6.85 2.585l5.13 5.13l5.132-5.13l4.284 4.284l-5.15 5.15l5.15 5.15l-4.246 4.247zm.578-5.307q.23-.233.23-.578t-.234-.574t-.577-.23t-.575.233t-.23.578t.233.575t.578.23t.575-.234m-4.155.314l2.85-2.85L6.85 4L4 6.85zm1.965 1.535q.345 0 .574-.233t.23-.578t-.233-.575t-.578-.23t-.574.234t-.23.577t.233.575t.578.23m2.19 1.382q.23-.233.23-.578t-.234-.574t-.577-.23t-.575.233t-.23.578t.233.574t.578.23t.575-.233m1.04-1.382q.345 0 .575-.233t.23-.578t-.233-.575t-.578-.23t-.575.234t-.23.577t.234.575t.578.23m-.911 2.75L17.15 20L20 17.15l-4.442-4.442zm1.97-.88");
}

</style>
