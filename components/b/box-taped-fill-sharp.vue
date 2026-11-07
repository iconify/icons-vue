<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv696bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-fill-sharp" /></template>
<style>
.qsv696bze {
  fill: currentColor;
  d: path("m9.758 3.107l-1.129-.558l2.928-1.446c.279-.137.607-.137.886 0L21 5.329l-3.371 1.665Zm-3.387.558l9 4.444L12 9.774L3 5.329ZM11 11.51v11.111l-8.443-4.169A1 1 0 0 1 2 17.556V7.066Zm2 0l9-4.444v10.49a1 1 0 0 1-.557.896L13 22.621Z");
}

</style>
