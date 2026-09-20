<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hzcc1nb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cube-16-filled" /></template>
<style>
.hzcc1nb-f {
  fill: currentColor;
  d: path("M6.923 1.378a3 3 0 0 1 2.154 0l4.962 1.908a1.5 1.5 0 0 1 .961 1.4v6.626a1.5 1.5 0 0 1-.961 1.4l-4.962 1.909a3 3 0 0 1-2.154 0l-4.961-1.909a1.5 1.5 0 0 1-.962-1.4V4.686a1.5 1.5 0 0 1 .962-1.4zM4.697 5.04a.5.5 0 0 0-.394.919L7.5 7.329v3.17a.5.5 0 0 0 1 0V7.33l3.197-1.37a.5.5 0 1 0-.394-.92L8 6.456z");
}

</style>
