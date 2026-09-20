<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh655obmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:iframe-outline-sharp" /></template>
<style>
.mh655obmw {
  fill: currentColor;
  d: path("M11.5 13.5h5v-2h-5zM10 15v-5h8v5zm-8 5V4h20v16zm2-2h16V8H4z");
}

</style>
