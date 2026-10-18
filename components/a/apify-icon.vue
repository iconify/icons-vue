<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z82co0bbo"/><path class="sehxzmboe"/><path class="nrcx7tb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apify-icon" /></template>
<style>
.nrcx7tb5e {
  fill: var(--svg-color--f86606, #f86606);
  d: path("M126.196 128.855L6.562 249.39c-2.43 2.446-.696 6.61 2.753 6.61h237.469c3.434 0 5.174-4.134 2.773-6.59L131.722 128.876a3.88 3.88 0 0 0-5.526-.02");
}

.sehxzmboe {
  fill: var(--svg-color--20a34e, #20a34e);
  d: path("M109.19 0H3.88A3.88 3.88 0 0 0 0 3.879V164.82c0 3.855 5.014 5.35 7.124 2.124L112.436 6.003C114.124 3.423 112.273 0 109.19 0");
}

.z82co0bbo {
  fill: var(--svg-color--246dff, #246dff);
  d: path("M146.81 0h105.31A3.88 3.88 0 0 1 256 3.879V164.82c0 3.855-5.014 5.35-7.124 2.124L143.564 6.003C141.876 3.423 143.727 0 146.81 0");
}

</style>
