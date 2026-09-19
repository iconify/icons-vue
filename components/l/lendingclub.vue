<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ml3fm1eci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lendingclub" /></template>
<style>
.ml3fm1eci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h7.75v7.75H5.5zm9.75 0H23v7.75h-7.75zm9.75 0h7.75v7.75H25zm9.75 0h7.75v7.75h-7.75zM5.5 15.25h7.75V23H5.5zm19.5 0h7.75V23H25zm9.75 0h7.75V23h-7.75zM5.5 25h7.75v7.75H5.5zm9.75 0H23v7.75h-7.75zM25 25h7.75v7.75H25zm9.75 0h7.75v7.75h-7.75zM5.5 34.75h7.75v7.75H5.5zm9.75 0H23v7.75h-7.75zm9.75 0h7.75v7.75H25zm9.75 0h7.75v7.75h-7.75z");
}

</style>
