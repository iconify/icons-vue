<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fajt6wb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-lock-sharp" /></template>
<style>
.fajt6wb3d {
  fill: currentColor;
  d: path("m12 12.116l8-5.231L19.692 6L12 11L4.308 6L4 6.885zM3 19V5h18v4.23h-.5q-2.027 0-3.456 1.463t-1.429 3.519V19zm14.616 0v-4.77h1v-1.114q0-.778.549-1.331q.549-.554 1.335-.554t1.336.554t.549 1.33v1.116h1V19zm1.769-4.77h2.23v-1.107q0-.471-.325-.797T20.5 12t-.79.326t-.326.797z");
}

</style>
