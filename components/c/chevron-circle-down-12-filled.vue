<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jz0rk-bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-down-12-filled" /></template>
<style>
.jz0rk-bsh {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1 0 10A5 5 0 0 1 6 1m1.854 4.854a.5.5 0 1 0-.708-.708L6 6.293L4.854 5.146a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0z");
}

</style>
