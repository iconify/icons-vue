<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="relhynbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:coin-stack-24-filled" /></template>
<style>
.relhynbgu {
  fill: currentColor;
  d: path("M19 7c0 2.761-3.134 5-7 5S5 9.761 5 7s3.134-5 7-5s7 2.239 7 5m-.38 3.37C17.18 11.958 14.752 13 12 13s-5.18-1.043-6.62-2.63A3.74 3.74 0 0 0 5 12c0 2.761 3.134 5 7 5s7-2.239 7-5c0-.57-.134-1.119-.38-1.63m0 5C17.18 16.958 14.752 18 12 18s-5.18-1.043-6.62-2.63A3.74 3.74 0 0 0 5 17c0 2.761 3.134 5 7 5s7-2.239 7-5c0-.57-.134-1.119-.38-1.63");
}

</style>
