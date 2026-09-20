<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ttnov_ryh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-20-filled" /></template>
<style>
.ttnov_ryh {
  fill: currentColor;
  d: path("M7.876 1.877a3 3 0 0 1 4.243 0l5.999 6a3 3 0 0 1 0 4.243l-5.999 5.998a3 3 0 0 1-4.243 0L1.878 12.12a3 3 0 0 1 0-4.244zm5.227 5.02a.5.5 0 0 0-.707 0L9.999 9.293L7.603 6.897a.5.5 0 0 0-.707.707l2.396 2.397l-2.396 2.396a.5.5 0 0 0 .707.707l2.396-2.396l2.397 2.396a.5.5 0 0 0 .707-.707l-2.397-2.396l2.397-2.397a.5.5 0 0 0 0-.707");
}

</style>
