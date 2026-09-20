<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wu-00sb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-up-left-bold" /></template>
<style>
.wu-00sb_y {
  fill: currentColor;
  d: path("M236 208a12 12 0 0 1-12 12H48a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12M72 156a12 12 0 0 0 12-12V77l91.51 91.52a12 12 0 0 0 17-17L101 60h67a12 12 0 0 0 0-24H72a12 12 0 0 0-12 12v96a12 12 0 0 0 12 12");
}

</style>
