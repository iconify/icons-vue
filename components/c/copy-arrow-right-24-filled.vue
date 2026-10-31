<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojwgxcn9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-24-filled" /></template>
<style>
.ojwgxcn9y {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-9 1.75a4.25 4.25 0 0 0 2.503 3.874a6.47 6.47 0 0 0 1.557 4.099a3.2 3.2 0 0 1-1.31.277h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zm9.854.896a.5.5 0 1 0-.707.707L19.293 17H14.5a.5.5 0 0 0 0 1h4.793l-1.646 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707zM18.75 2A3.25 3.25 0 0 1 22 5.25v7.562a6.502 6.502 0 0 0-10.929 3.722A3.25 3.25 0 0 1 9.5 13.75v-8.5A3.25 3.25 0 0 1 12.75 2z");
}

</style>
