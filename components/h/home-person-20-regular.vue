<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a7k1berjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-person-20-regular" /></template>
<style>
.a7k1berjm {
  fill: currentColor;
  d: path("M16.5 14a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S11 16.75 11 15.5a1.5 1.5 0 0 1 1.5-1.5zM8.996 2.385a1.5 1.5 0 0 1 2.008 0l5.5 4.95A1.5 1.5 0 0 1 17 8.45v.893a3 3 0 0 0-1.006-.942a.5.5 0 0 0-.159-.322l-5.5-4.95a.5.5 0 0 0-.67 0l-5.5 4.95a.5.5 0 0 0-.165.37v7.056a.5.5 0 0 0 .5.5h5.54c.052.343.162.681.33 1H4.5a1.5 1.5 0 0 1-1.5-1.5V8.45c0-.425.18-.83.496-1.114zM14.5 9a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
