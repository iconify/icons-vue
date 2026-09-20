<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppwrgkbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-1-outline-sharp" /></template>
<style>
.ppwrgkbxe {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm5-2h12.5V8H6zm15.5-1.5v-5H23v5z");
}

</style>
