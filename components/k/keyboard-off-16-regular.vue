<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wb7d8jq5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-off-16-regular" /></template>
<style>
.wb7d8jq5r {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L12.293 13H2.75A1.75 1.75 0 0 1 1 11.25v-6.5a1.75 1.75 0 0 1 1.342-1.701L1.146 1.854a.5.5 0 0 1 0-.707M13.25 3c.966 0 1.75.784 1.75 1.75v6.5c0 .452-.173.863-.455 1.174l-.71-.71A.74.74 0 0 0 14 11.25v-6.5a.75.75 0 0 0-.75-.75H6.121l-1-1zM2.75 4a.75.75 0 0 0-.75.75v6.5c0 .414.336.75.75.75h8.543l-1-1H3.5a.5.5 0 1 1 0-1h5.793l-6-6zm2.5 3.5a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m6 0a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m-8-2a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m6 0a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m3 0a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
