<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rera8xt7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:card-travel-sharp" /></template>
<style>
.rera8xt7n {
  fill: currentColor;
  d: path("M2 21V6h5V2h10v4h5v15zM9 6h6V4H9zM4 17h16v-3H4z");
}

</style>
