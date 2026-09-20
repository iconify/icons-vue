<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb31sabuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-footer-24-filled" /></template>
<style>
.xb31sabuj {
  fill: currentColor;
  d: path("M17.75 2a2.25 2.25 0 0 1 2.245 2.096L20 4.25v15.5a2.25 2.25 0 0 1-2.096 2.245L17.75 22H6.25a2.25 2.25 0 0 1-2.245-2.096L4 19.75V4.25a2.25 2.25 0 0 1 2.096-2.245L6.25 2zM7.005 6.505a1.5 1.5 0 0 0 1.5 1.5h7a1.5 1.5 0 0 0 0-3h-7a1.5 1.5 0 0 0-1.5 1.5m0 11a1.5 1.5 0 0 0 1.5 1.5h7a1.5 1.5 0 0 0 0-3h-7a1.5 1.5 0 0 0-1.5 1.5");
}

</style>
