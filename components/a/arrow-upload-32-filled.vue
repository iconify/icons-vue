<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgx7l2mdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-upload-32-filled" /></template>
<style>
.mgx7l2mdu {
  fill: currentColor;
  d: path("M7.25 2a1.25 1.25 0 1 0 0 2.5h17.5a1.25 1.25 0 1 0 0-2.5zm9.634 4.866a1.25 1.25 0 0 0-1.768 0l-6.75 6.75a1.25 1.25 0 0 0 1.768 1.768l4.616-4.616V28.75a1.25 1.25 0 1 0 2.5 0V10.768l4.616 4.616a1.25 1.25 0 0 0 1.768-1.768z");
}

</style>
