<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkv8ud7kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-landscape-2-outline-sharp" /></template>
<style>
.hkv8ud7kx {
  fill: currentColor;
  d: path("M13 14h5V8h-5zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
