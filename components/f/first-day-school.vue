<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egiw2v8rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:first-day-school" /></template>
<style>
.egiw2v8rv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 4.992q1.671.456 2.986 1.772q2.014 2.013 2.014 4.861v3.75q0 2.848-2.014 4.861q-.47.471-.986.831V16q0-2.25-2.25-2.25h-5q-2.25 0-2.25 2.25v5.067q-.516-.36-.986-.831q-2.014-2.013-2.014-4.861v-3.75q0-2.848 2.014-4.861Q7.579 5.448 9.25 4.992V4.5q0-2.75 2.75-2.75t2.75 2.75zm-6.073 16.83q1.136.428 2.448.428h1.75q1.312 0 2.448-.428q-.073-.153-.073-.322V16q0-.75-.75-.75h-5q-.75 0-.75.75v5.5q0 .169-.073.322M10.75 4.759q.186-.009.375-.009h1.75q.189 0 .375.009V4.5q0-1.25-1.25-1.25T10.75 4.5z");
}

</style>
