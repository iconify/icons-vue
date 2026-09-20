<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ak_5xhb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-20-filled" /></template>
<style>
.ak_5xhb8k {
  fill: currentColor;
  d: path("M3.5 4A1.5 1.5 0 0 0 2 5.5v8A1.5 1.5 0 0 0 3.5 15h13a1.5 1.5 0 0 0 1.5-1.5v-8A1.5 1.5 0 0 0 16.5 4zm2.755 3.252a.752.752 0 1 1-1.505 0a.752.752 0 0 1 1.505 0m6 0a.752.752 0 1 1-1.505 0a.752.752 0 0 1 1.505 0M5 12.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5m9.502-4.495a.752.752 0 1 1 0-1.505a.752.752 0 0 1 0 1.505m-7.504 2.5a.752.752 0 1 1 0-1.505a.752.752 0 0 1 0 1.505m3.757-.753a.752.752 0 1 1-1.505 0a.752.752 0 0 1 1.505 0m2.252.753a.752.752 0 1 1 0-1.505a.752.752 0 0 1 0 1.505M9.255 7.252a.752.752 0 1 1-1.505 0a.752.752 0 0 1 1.505 0");
}

</style>
