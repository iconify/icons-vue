<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wppyv6b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bubbles-outline-sharp" /></template>
<style>
.wppyv6b7v {
  fill: currentColor;
  d: path("m9.723 8.4l4.162 4.156V9.619h1v4.65h-4.65v-1h2.961l-4.18-4.161zM18.577 19q-1.01 0-1.716-.707t-.707-1.716t.707-1.716t1.716-.707t1.716.707t.707 1.716t-.707 1.716t-1.716.707M3 19V5h18v6.73h-1V6H4v12h9.73v1z");
}

</style>
