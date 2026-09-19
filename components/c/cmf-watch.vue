<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0bjnabvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cmf-watch" /></template>
<style>
.v0bjnabvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.487 26.415C40.632 36.789 30.92 43.888 20.794 42.27S3.966 30.93 5.821 20.556C7.068 13.584 11.982 7.786 18.585 5.5m10.052.558l12.854 12.39");
}

</style>
