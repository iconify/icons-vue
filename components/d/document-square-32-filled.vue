<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hk5u9mbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-square-32-filled" /></template>
<style>
.hk5u9mbqq {
  fill: currentColor;
  d: path("M18 10.75A3.25 3.25 0 0 0 21.25 14H29v11.75A3.25 3.25 0 0 1 25.75 29H6.25A3.25 3.25 0 0 1 3 25.75V6.25A3.25 3.25 0 0 1 6.25 3H18zm2-7.613a3.25 3.25 0 0 1 1.366.815l6.682 6.682c.384.384.662.855.815 1.366H21.25c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
