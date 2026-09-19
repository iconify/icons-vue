<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuvw7qbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-south" /></template>
<style>
.fuvw7qbuz {
  fill: currentColor;
  d: path("m19 15l-1.41-1.41L13 18.17V2h-2v16.17l-4.59-4.59L5 15l7 7z");
}

</style>
