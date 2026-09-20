<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nhoez6b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-x-20-filled" /></template>
<style>
.nhoez6b3a {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m3.354 4.646a.5.5 0 0 0-.707 0L10 9.293L7.354 6.646a.5.5 0 1 0-.708.708L9.293 10l-2.647 2.646a.5.5 0 1 0 .708.707L10 10.708l2.646 2.646a.5.5 0 1 0 .707-.707L10.708 10l2.646-2.646a.5.5 0 0 0 0-.708");
}

</style>
