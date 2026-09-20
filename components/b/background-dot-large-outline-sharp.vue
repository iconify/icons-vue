<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfbxucc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:background-dot-large-outline-sharp" /></template>
<style>
.hfbxucc5i {
  fill: currentColor;
  d: path("M9.563 16.563Q10 16.125 10 15.5t-.437-1.062T8.5 14t-1.062.438T7 15.5t.438 1.063T8.5 17t1.063-.437m0-7Q10 9.125 10 8.5t-.437-1.062T8.5 7t-1.062.438T7 8.5t.438 1.063T8.5 10t1.063-.437m7 7Q17 16.125 17 15.5t-.437-1.062T15.5 14t-1.062.438T14 15.5t.438 1.063T15.5 17t1.063-.437m0-7Q17 9.125 17 8.5t-.437-1.062T15.5 7t-1.062.438T14 8.5t.438 1.063T15.5 10t1.063-.437M3 21V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
