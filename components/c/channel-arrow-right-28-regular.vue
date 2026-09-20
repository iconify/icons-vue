<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zl8v50bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-28-regular" /></template>
<style>
.zl8v50bxq {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m-16 6.75a2.75 2.75 0 0 0 2.75 2.75h6.376A7.5 7.5 0 0 0 14.5 25H7.25A4.25 4.25 0 0 1 3 20.75v-9.353a2.75 2.75 0 0 0 1.5 0zm17.354-3.604a.5.5 0 1 0-.707.707L23.293 20H16.5a.5.5 0 0 0 0 1h6.793l-2.146 2.146a.5.5 0 1 0 .707.707l3-3a.503.503 0 0 0 0-.707zM15.402 15a7.5 7.5 0 0 0-1.245 1.5H9.75a.75.75 0 0 1 0-1.5zM20.75 3A4.25 4.25 0 0 1 25 7.25v7.25a7.5 7.5 0 0 0-1.5-.874V7.25a2.75 2.75 0 0 0-2.75-2.75H7.25a2.75 2.75 0 0 0-2.532 1.675a2.74 2.74 0 0 0-1.55-.113A4.25 4.25 0 0 1 7.25 3zm-2.5 8a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5zM3.75 7a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
