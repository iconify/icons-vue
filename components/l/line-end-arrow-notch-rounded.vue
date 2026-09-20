<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9kts16cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-arrow-notch-rounded" /></template>
<style>
.g9kts16cf {
  fill: currentColor;
  d: path("M13.527 15.983q-.273.161-.49-.044t-.076-.497l1.637-2.942H3q-.213 0-.357-.143T2.5 12t.143-.357T3 11.5h11.598l-1.636-2.942q-.143-.293.075-.497t.49-.044l5.187 3.306q.378.243.378.677t-.378.677z");
}

</style>
