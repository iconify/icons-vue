<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vitunrbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-arrow-down-24-filled" /></template>
<style>
.vitunrbbh {
  fill: currentColor;
  d: path("M17.75 2a2.25 2.25 0 0 1 2.245 2.096L20 4.25v7.248A6.5 6.5 0 0 0 12.81 22H6.25a2.25 2.25 0 0 1-2.245-2.096L4 19.75V4.25a2.25 2.25 0 0 1 2.096-2.245L6.25 2zM8.505 5.005a1.5 1.5 0 0 0 0 3h7a1.5 1.5 0 0 0 0-3zM23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-5-3a.5.5 0 0 0-1 0v4.793l-1.646-1.647a.5.5 0 0 0-.708.708l2.5 2.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 0 0-.708-.708L18 19.293z");
}

</style>
