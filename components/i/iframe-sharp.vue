<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ka0jbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:iframe-sharp" /></template>
<style>
.k_ka0jbrj {
  fill: currentColor;
  d: path("M10 15v-5h8v5zm-8 5V4h20v16zm2-2h16V8H4z");
}

</style>
