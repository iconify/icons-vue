<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c724yg_nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-24-regular" /></template>
<style>
.c724yg_nb {
  fill: currentColor;
  d: path("M11.499 4a6.5 6.5 0 0 0-.422 1.5H4.25a.75.75 0 0 0-.75.75V8h7.676c.166.705.448 1.365.824 1.96v7.29A2.75 2.75 0 0 1 9.25 20h-4.5A2.75 2.75 0 0 1 2 17.25v-11A2.25 2.25 0 0 1 4.25 4zM22 19.25a.75.75 0 0 1-1.5 0v-6.984a6.5 6.5 0 0 0 1.5-1.078zm-18.5-2c0 .69.56 1.25 1.25 1.25h4.5c.69 0 1.25-.56 1.25-1.25V9.5h-7zm4.75-5.75a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5zM17.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m3.354 3.146a.5.5 0 0 0-.707 0L16.5 7.793l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708");
}

</style>
