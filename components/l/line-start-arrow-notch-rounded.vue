<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyf3uob1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-arrow-notch-rounded" /></template>
<style>
.wyf3uob1h {
  fill: currentColor;
  d: path("m9.402 12.5l1.636 2.942q.143.293-.075.497t-.49.044l-5.187-3.306q-.378-.242-.378-.677t.378-.677l5.187-3.306q.273-.161.49.044t.076.497L9.402 11.5H21q.214 0 .357.143T21.5 12t-.143.357T21 12.5z");
}

</style>
