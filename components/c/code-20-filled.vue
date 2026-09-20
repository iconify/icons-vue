<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gzl7me1ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-20-filled" /></template>
<style>
.gzl7me1ev {
  fill: currentColor;
  d: path("M12.937 4.052a.75.75 0 0 0-1.373-.604l-5.5 12.5a.75.75 0 1 0 1.372.604zm1.356 9.793a.75.75 0 0 1-.137-1.052L16.304 10l-2.148-2.793a.75.75 0 0 1 1.188-.914l2.5 3.25a.75.75 0 0 1 0 .915l-2.5 3.25a.75.75 0 0 1-1.051.137m-8.586-7.69a.75.75 0 0 1 .137 1.053L3.696 10l2.148 2.793a.75.75 0 1 1-1.188.915l-2.5-3.25a.75.75 0 0 1 0-.915l2.5-3.25a.75.75 0 0 1 1.051-.137");
}

</style>
