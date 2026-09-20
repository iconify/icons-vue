<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ledy04cbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:closed-caption-outline-sharp" /></template>
<style>
.ledy04cbl {
  fill: currentColor;
  d: path("M3 20V4h18v16zm2-2h14V6H5zm1-3h5v-2H9.5v.5h-2v-3h2v.5H11V9H6zm7 0h5v-2h-1.5v.5h-2v-3h2v.5H18V9h-5zm-8 3V6z");
}

</style>
