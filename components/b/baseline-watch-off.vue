<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wust90z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-watch-off" /></template>
<style>
.s-wust90z {
  fill: currentColor;
  d: path("M12 7c2.76 0 5 2.24 5 5c0 .64-.13 1.25-.35 1.82l1.5 1.5a6.96 6.96 0 0 0-1.79-8.79L15 2H9l-.96 3.21l2.14 2.14C10.75 7.13 11.36 7 12 7M2.81 2.81L1.39 4.22l4.46 4.46a6.96 6.96 0 0 0 1.79 8.79L9 22h6l.96-3.21l3.82 3.82l1.41-1.41zM12 17c-2.76 0-5-2.24-5-5c0-.64.13-1.25.35-1.82l6.47 6.47c-.57.22-1.18.35-1.82.35");
}

</style>
