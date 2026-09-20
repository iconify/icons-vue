<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa0wt58ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-saver-outline" /></template>
<style>
.aa0wt58ci {
  fill: currentColor;
  d: path("M16.385 21v-2.616h-2.616v-1h2.615V14.77h1v2.615H20v1h-2.616V21zm-7.693 0q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v6.903q-.275.039-.516.088t-.484.128V5.462H8.885V20h2.561q.104.287.228.527t.293.473z");
}

</style>
