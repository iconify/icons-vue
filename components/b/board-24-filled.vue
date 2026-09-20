<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvq9g-bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-24-filled" /></template>
<style>
.yvq9g-bvn {
  fill: currentColor;
  d: path("M11.5 21H6.25A3.25 3.25 0 0 1 3 17.75V9.5h8.5zm9.5-3.25A3.25 3.25 0 0 1 17.75 21H13v-5h8zM17.75 3A3.25 3.25 0 0 1 21 6.25v8.25h-8V3zM11.5 8H3V6.25A3.25 3.25 0 0 1 6.25 3h5.25z");
}

</style>
