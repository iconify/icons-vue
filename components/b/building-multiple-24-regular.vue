<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4naewn9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-multiple-24-regular" /></template>
<style>
.h4naewn9g {
  fill: currentColor;
  d: path("M8 6a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 2a1 1 0 1 1-2 0a1 1 0 0 1 2 0m0 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m7-3a1 1 0 1 0 0-2a1 1 0 0 0 0 2m3 0a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0-3a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-2-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m2-2a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-2-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1-4v-.75A2.25 2.25 0 0 0 11.75 2h-6.5A2.25 2.25 0 0 0 3 4.25v16.5c0 .414.336.75.75.75h16.5a.75.75 0 0 0 .75-.75V7.25A2.25 2.25 0 0 0 18.75 5zm-9.5-.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 .75.75V5h-.25A2.25 2.25 0 0 0 10 7.25V20H4.5zM14.5 20v-1.5h2V20zm3.5-2.25a.75.75 0 0 0-.75-.75h-3.5a.75.75 0 0 0-.75.75V20h-1.5V7.25a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 .75.75V20H18z");
}

</style>
