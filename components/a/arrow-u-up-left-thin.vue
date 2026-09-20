<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="reuy5h1ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-up-left-thin" /></template>
<style>
.reuy5h1ge {
  fill: currentColor;
  d: path("M228 144a60.07 60.07 0 0 1-60 60H80a4 4 0 0 1 0-8h88a52 52 0 0 0 0-104H41.66l41.17 41.17a4 4 0 0 1-5.66 5.66l-48-48a4 4 0 0 1 0-5.66l48-48a4 4 0 0 1 5.66 5.66L41.66 84H168a60.07 60.07 0 0 1 60 60");
}

</style>
