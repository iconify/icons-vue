<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujy4r3azr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-view-outline-sharp" /></template>
<style>
.ujy4r3azr {
  fill: currentColor;
  d: path("M4 11V4h7v7zm0 9v-7h7v7zm9-9V4h7v7zm0 9v-7h7v7zM5 10h5V5H5zm9 0h5V5h-5zm0 9h5v-5h-5zm-9 0h5v-5H5zm5-9");
}

</style>
