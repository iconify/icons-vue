<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e4xta_bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-16-regular" /></template>
<style>
.e4xta_bpw {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2m0 1q.28 0 .555.03a.5.5 0 0 1-.11.994a4 4 0 0 0-2.959 7.087a.5.5 0 0 1-.63.778A5 5 0 0 1 8 3m4.418 4.003a.5.5 0 0 1 .552.442Q13 7.72 13 8c0 1.57-.725 2.973-1.856 3.889a.5.5 0 0 1-.63-.778a3.99 3.99 0 0 0 1.462-3.556a.5.5 0 0 1 .442-.552m-2.207-2.07c.29-.192.584-.507.92-.416a.5.5 0 0 1 .354.357c.087.335-.224.625-.415.913c-.567.858-1.813 2.722-2.186 3.095a1.25 1.25 0 0 1-1.768-1.768c.373-.372 2.235-1.615 3.095-2.181");
}

</style>
