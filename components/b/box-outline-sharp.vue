<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfw0oebbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:box-outline-sharp" /></template>
<style>
.nfw0oebbq {
  fill: currentColor;
  d: path("M5 8v11h14V8h-3v8l-4-2l-4 2V8zM3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25zM10 8v4.75l2-1l2 1V8zM5 8h14z");
}

</style>
