<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s06x40c9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-four-24-filled" /></template>
<style>
.s06x40c9p {
  fill: currentColor;
  d: path("M3 8v3.25h18V8zm18-1.5v-.25A3.25 3.25 0 0 0 17.75 3H6.25A3.25 3.25 0 0 0 3 6.25v.25zM3 16v-3.25h18V16zm0 1.5v.25A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75v-.25z");
}

</style>
