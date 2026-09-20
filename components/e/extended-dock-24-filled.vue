<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrv_mxbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:extended-dock-24-filled" /></template>
<style>
.yrv_mxbne {
  fill: currentColor;
  d: path("M6.25 10.997c.966 0 1.75.784 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 2 15.247v-2.5c0-.966.784-1.75 1.75-1.75zm7 0c.966 0 1.75.784 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 15.247v-2.5c0-.966.784-1.75 1.75-1.75zm7 0c.966 0 1.75.784 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2.5c0-.966.784-1.75 1.75-1.75zM7.97 7.72l3.5-3.5a.75.75 0 0 1 .968-.079l.085.071l3.602 3.5a.75.75 0 0 1-.96 1.147l-.085-.071l-3.072-2.985L9.03 8.78a.75.75 0 0 1-1.133-.976zl3.5-3.5z");
}

</style>
