<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p64j6ab9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-16-filled" /></template>
<style>
.p64j6ab9r {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11m-.64 1.53c.108-.686 1.038-.728 1.248-.129l.033.128c.184 1.192.38 2.382.54 3.576c.038.278.069.53.069.646a1.25 1.25 0 0 1-2.5 0c0-.116.031-.368.068-.646c.12-.895.378-2.543.541-3.576");
}

</style>
