<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kosbifw4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:closed-caption-sharp" /></template>
<style>
.kosbifw4e {
  fill: currentColor;
  d: path("M3 20V4h18v16zm3-5h5v-2H9.5v.5h-2v-3h2v.5H11V9H6zm7 0h5v-2h-1.5v.5h-2v-3h2v.5H18V9h-5z");
}

</style>
