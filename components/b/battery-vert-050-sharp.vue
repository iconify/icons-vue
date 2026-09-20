<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzxd0nn_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-vert-050-sharp" /></template>
<style>
.qzxd0nn_c {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18H7Zm2-9h6V6H9v7Z");
}

</style>
