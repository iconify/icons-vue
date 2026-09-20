<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rgh6z1imf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-28-filled" /></template>
<style>
.rgh6z1imf {
  fill: currentColor;
  d: path("M15.408 3.498a2.25 2.25 0 0 0-2.816 0l-7.75 6.217A2.25 2.25 0 0 0 4 11.47v11.28A2.25 2.25 0 0 0 6.25 25h2.5A2.25 2.25 0 0 0 11 22.75v-5.5c0-.69.56-1.25 1.25-1.25h3.5c.69 0 1.25.56 1.25 1.25v5.5A2.25 2.25 0 0 0 19.25 25h2.5A2.25 2.25 0 0 0 24 22.75V11.47a2.25 2.25 0 0 0-.842-1.755z");
}

</style>
