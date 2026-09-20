<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fxytrd97z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:briefcase-simple-bold" /></template>
<style>
.fxytrd97z {
  d: path("M216.008 56H180v-8a28.031 28.031 0 0 0-28-28h-48a28.031 28.031 0 0 0-28 28v8H40.008a20.022 20.022 0 0 0-20 20v128a20.022 20.022 0 0 0 20 20h176a20.022 20.022 0 0 0 20-20V76a20.022 20.022 0 0 0-20-20zM100 48a4.004 4.004 0 0 1 4-4h48a4.004 4.004 0 0 1 4 4v8h-56zm112.008 152h-168V80h168z");
  fill: currentColor;
}

</style>
