<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9jdsgzkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-markdown-24-regular" /></template>
<style>
.i9jdsgzkj {
  fill: currentColor;
  d: path("M13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v7.92a1.74 1.74 0 0 0-1.5 0V6.25a.75.75 0 0 0-.75-.75h-2.129c-.404.603-1.09 1-1.871 1h-3.5c-.78 0-1.467-.397-1.871-1H6.25a.75.75 0 0 0-.75.75v13.5c0 .414.336.75.75.75H7v.75c0 .269.063.522.17.75h-.92A2.25 2.25 0 0 1 4 19.75V6.25A2.25 2.25 0 0 1 6.25 4h1.764a2.25 2.25 0 0 1 2.236-2zm.672 13.02a.75.75 0 0 1 .578.73v5.5a.75.75 0 0 1-1.5 0v-2.323l-1.33 2.658a.75.75 0 0 1-1.34 0L9.5 18.927v2.323a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 1.42-.335l2.08 4.158l2.08-4.158a.75.75 0 0 1 .842-.394M19.25 15a.75.75 0 0 1 .75.75v3.69l1.22-1.22a.75.75 0 1 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-1.06 0l-2.5-2.5a.75.75 0 1 1 1.06-1.06l1.22 1.22v-3.69a.75.75 0 0 1 .75-.75m-9-11.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
