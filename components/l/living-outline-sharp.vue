<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m71t1hbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:living-outline-sharp" /></template>
<style>
.m71t1hbat {
  fill: currentColor;
  d: path("M2 22V2h20v20zm2-2h16V4H4zm1-2h14v-7.65h-1.25V6H6.25v4.35H5zm1.5-1.5v-5h2v3h7v-3h2v5zM10 13v-2.95H7.75V7.5h8.5v2.55H14V13zm-6 7V4z");
}

</style>
