<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og4e6_85k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-roller-shades" /></template>
<style>
.og4e6_85k {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM6 19v-6h5v1.8c-.4.3-.8.8-.8 1.4c0 1 .8 1.8 1.8 1.8s1.8-.8 1.8-1.8c0-.6-.3-1.1-.8-1.4V13h5v6z");
}

</style>
