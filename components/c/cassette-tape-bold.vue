<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qumdhj1ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cassette-tape-bold" /></template>
<style>
.qumdhj1ci {
  fill: currentColor;
  d: path("M224 44H32a20 20 0 0 0-20 20v128a20 20 0 0 0 20 20h192a20 20 0 0 0 20-20V64a20 20 0 0 0-20-20m-4 144h-37l-12.6-16.8a8 8 0 0 0-6.4-3.2H92a8 8 0 0 0-6.4 3.2L73 188H36V68h184ZM82 152h92a34 34 0 0 0 0-68H82a34 34 0 0 0 0 68m0-44a10 10 0 1 1-10 10a10 10 0 0 1 10-10m102 10a10 10 0 1 1-10-10a10 10 0 0 1 10 10m-42.5 10h-27a34.1 34.1 0 0 0 0-20h27a34.1 34.1 0 0 0 0 20");
}

</style>
