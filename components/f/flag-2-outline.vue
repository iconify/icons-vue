<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ctpp4xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-2-outline" /></template>
<style>
.c1ctpp4xq {
  fill: currentColor;
  d: path("M6 21V4h14l-2.096 4.27L20 12.538H7V21zm1-9.461h11.416l-1.624-3.27L18.416 5H7zm0 0V5z");
}

</style>
