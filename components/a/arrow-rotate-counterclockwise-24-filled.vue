<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a077vr0gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-24-filled" /></template>
<style>
.a077vr0gn {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 1 9 9a1 1 0 1 1-2 0a7 7 0 1 0-11 5.743V16a1 1 0 1 1 2 0v4a1 1 0 0 1-1 1H5a1 1 0 1 1 0-2h1.347A9 9 0 0 1 12 3m0 6a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 2a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
