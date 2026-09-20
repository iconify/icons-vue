<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzr_tuqck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bowl-chopsticks-24-regular" /></template>
<style>
.xzr_tuqck {
  fill: currentColor;
  d: path("M6.4 2.376a.75.75 0 0 0-1.3.748L9.635 11H2.75a.75.75 0 0 0-.75.75V12c0 5.523 4.477 10 10 10s10-4.477 10-10v-.25a.75.75 0 0 0-.75-.75h-5.885L10.4 2.376a.75.75 0 0 0-1.3.748L13.635 11h-2.27zM4.788 16.5h14.424a8.5 8.5 0 0 1-7.212 4a8.5 8.5 0 0 1-7.212-4M4.045 15a8.5 8.5 0 0 1-.53-2.5h16.97a8.5 8.5 0 0 1-.53 2.5z");
}

</style>
