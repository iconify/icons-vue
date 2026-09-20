<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mjca1xbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:clock-countdown-bold" /></template>
<style>
.mjca1xbnd {
  fill: currentColor;
  d: path("M236 137A108.13 108.13 0 1 1 119 20a12 12 0 0 1 2 24a84.12 84.12 0 1 0 91 91a12 12 0 1 1 24 2M116 76v52a12 12 0 0 0 12 12h52a12 12 0 0 0 0-24h-40V76a12 12 0 0 0-24 0m92 20a16 16 0 1 0-16-16a16 16 0 0 0 16 16m-32-32a16 16 0 1 0-16-16a16 16 0 0 0 16 16");
}

</style>
