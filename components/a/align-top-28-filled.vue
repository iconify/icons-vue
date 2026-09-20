<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ccj8rzuco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-top-28-filled" /></template>
<style>
.ccj8rzuco {
  fill: currentColor;
  d: path("M2.75 3a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5zM5 8.75A2.75 2.75 0 0 1 7.75 6h2.5A2.75 2.75 0 0 1 13 8.75v13.5A2.75 2.75 0 0 1 10.25 25h-2.5A2.75 2.75 0 0 1 5 22.25zm10 0A2.75 2.75 0 0 1 17.75 6h2.5A2.75 2.75 0 0 1 23 8.75v8a2.75 2.75 0 0 1-2.75 2.75h-2.5A2.75 2.75 0 0 1 15 16.75z");
}

</style>
