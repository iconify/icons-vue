<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpqbhosqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-outline-sharp" /></template>
<style>
.mpqbhosqj {
  fill: currentColor;
  d: path("M2 20V4h20v16zm10-7L4 8v10h16V8zm0-2l8-5H4zM4 8V6v12z");
}

</style>
