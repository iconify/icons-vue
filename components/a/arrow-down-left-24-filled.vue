<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjwqorb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-24-filled" /></template>
<style>
.wjwqorb2u {
  fill: currentColor;
  d: path("M13 21a1 1 0 0 0 0-2H6.414L20.707 4.707a1 1 0 0 0-1.414-1.414L5 17.586V11a1 1 0 1 0-2 0v9a1 1 0 0 0 1 1z");
}

</style>
