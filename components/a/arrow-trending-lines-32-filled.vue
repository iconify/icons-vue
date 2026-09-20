<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zsmr5f8-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-trending-lines-32-filled" /></template>
<style>
.zsmr5f8-f {
  fill: currentColor;
  d: path("M4.75 23c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 1 1-2.5 0v-3.5c0-.69.56-1.25 1.25-1.25m7-6c.69 0 1.25.56 1.25 1.25v9.5a1.25 1.25 0 1 1-2.5 0v-9.5c0-.69.56-1.25 1.25-1.25m7 3c.69 0 1.25.56 1.25 1.25v6.5a1.25 1.25 0 1 1-2.5 0v-6.5c0-.69.56-1.25 1.25-1.25m7-6c.69 0 1.25.56 1.25 1.25v12.5a1.25 1.25 0 1 1-2.5 0v-12.5c0-.69.56-1.25 1.25-1.25m2-11c.69 0 1.25.56 1.25 1.25v5.5a1.25 1.25 0 1 1-2.5 0V7.268l-7.866 7.866a1.25 1.25 0 0 1-1.768 0l-4.116-4.116l-7.116 7.116a1.25 1.25 0 1 1-1.768-1.768l8-8l.095-.086a1.25 1.25 0 0 1 1.673.086l4.116 4.116L24.732 5.5H22.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
