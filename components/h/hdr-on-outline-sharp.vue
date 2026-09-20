<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh079ob6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hdr-on-outline-sharp" /></template>
<style>
.vh079ob6x {
  fill: currentColor;
  d: path("M16 15V9h4.25l.75.75v2.4l-.75.75h-.15L21 15h-1.5l-.9-2h-1.1v2zm1.5-3.5h2v-1h-2zM3 15V9h1.5v2h2V9H8v6H6.5v-2.5h-2V15zm6.5 0V9h4.25l.75.75v4.5l-.75.75zm1.5-1.5h2v-3h-2z");
}

</style>
