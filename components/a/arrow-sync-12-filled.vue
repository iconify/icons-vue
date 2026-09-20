<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="su71ymkvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-12-filled" /></template>
<style>
.su71ymkvu {
  fill: currentColor;
  d: path("M7.423 2.925a.6.6 0 0 0 0-.849L6.173.826a.6.6 0 0 0-.849.849l.248.247a4.1 4.1 0 0 0-2.75 6.67a.6.6 0 0 0 .93-.759A2.9 2.9 0 0 1 5.51 3.141l-.186.185a.6.6 0 0 0 .849.849zm.701.23a.6.6 0 0 0-.022.85A2.9 2.9 0 0 1 6.488 8.86l.185-.185a.6.6 0 0 0-.849-.849l-1.25 1.25a.6.6 0 0 0 0 .849l1.25 1.25a.6.6 0 0 0 .849-.849l-.248-.248a4.1 4.1 0 0 0 2.547-6.9a.6.6 0 0 0-.848-.022");
}

</style>
