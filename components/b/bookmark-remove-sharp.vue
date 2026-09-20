<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnz6xqbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-remove-sharp" /></template>
<style>
.wnz6xqbsm {
  fill: currentColor;
  d: path("M20 7h-5V6h5zM6 19.5V4h7.77q-.386.596-.578 1.197T13 6.5q0 1.742 1.157 3.012T17 10.958q.287.036.5.036t.5-.036V19.5l-6-2.577z");
}

</style>
