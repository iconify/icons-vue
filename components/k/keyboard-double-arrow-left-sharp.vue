<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8artkoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-double-arrow-left-sharp" /></template>
<style>
.zq8artkoq {
  fill: currentColor;
  d: path("M11.25 17.308L5.942 12l5.308-5.308l.708.708L7.364 12l4.594 4.6zm6.1 0L12.042 12l5.308-5.308l.708.708l-4.594 4.6l4.594 4.6z");
}

</style>
