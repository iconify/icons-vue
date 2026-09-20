<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="js5xo_ujd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-48-filled" /></template>
<style>
.js5xo_ujd {
  fill: currentColor;
  d: path("M12.25 6A6.25 6.25 0 0 0 6 12.25v23.5c0 1.356.432 2.61 1.165 3.635l14.36-14.36a3.5 3.5 0 0 1 4.95 0l14.36 14.36A6.22 6.22 0 0 0 42 35.75v-23.5A6.25 6.25 0 0 0 35.75 6zM34.5 17.5a4 4 0 1 1-8 0a4 4 0 0 1 8 0m4.502 23.588L24.707 26.793a1 1 0 0 0-1.414 0L8.998 41.088A6.2 6.2 0 0 0 12.25 42h23.5a6.2 6.2 0 0 0 3.252-.912");
}

</style>
