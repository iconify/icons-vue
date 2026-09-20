<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gtmpd10pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-out-line-vertical-bold" /></template>
<style>
.gtmpd10pe {
  fill: currentColor;
  d: path("M228 128a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12M104.49 56.48L116 45v43a12 12 0 0 0 24 0V45l11.51 11.51a12 12 0 0 0 17-17l-32-32a12 12 0 0 0-17 0l-32 32a12 12 0 0 0 17 17Zm47 143L140 211v-43a12 12 0 0 0-24 0v43l-11.51-11.52a12 12 0 0 0-17 17l32 32a12 12 0 0 0 17 0l32-32a12 12 0 0 0-17-17");
}

</style>
