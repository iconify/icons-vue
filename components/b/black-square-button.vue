<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="poyjmcwjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-square-button" /></template>
<style>
.poyjmcwjh {
  fill: currentColor;
  d: path("M2 2v60h60V2zm52 52H10V10h44z");
}

</style>
