<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7hn0fh2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-vert-020-sharp" /></template>
<style>
.o7hn0fh2x {
  fill: currentColor;
  d: path("M9 17h6V6H9v11Zm-2 5V4h3V2h4v2h3v18H7Z");
}

</style>
