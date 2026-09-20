<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpr2rkb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-full-sharp" /></template>
<style>
.kpr2rkb5k {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-6h16V6H4z");
}

</style>
