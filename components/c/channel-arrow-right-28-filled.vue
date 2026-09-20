<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="td34o-_rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-28-filled" /></template>
<style>
.td34o-_rt {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m.25-11A4.25 4.25 0 0 1 25 7.25v7.25a7.47 7.47 0 0 0-4.5-1.5c-1.969 0-3.76.76-5.098 2H9.75a.75.75 0 0 0 0 1.5h4.407a7.46 7.46 0 0 0-1.157 4c0 1.689.558 3.247 1.5 4.5H7.25A4.25 4.25 0 0 1 3 20.75v-9.353A2.753 2.753 0 0 0 6.5 8.75a2.75 2.75 0 0 0-3.332-2.688A4.25 4.25 0 0 1 7.25 3zm1.104 14.147a.5.5 0 1 0-.707.707L23.293 20H16.5a.5.5 0 0 0 0 1h6.793l-2.146 2.146a.5.5 0 1 0 .707.707l3-3a.503.503 0 0 0 0-.707zM9.75 11a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm-6-4a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
