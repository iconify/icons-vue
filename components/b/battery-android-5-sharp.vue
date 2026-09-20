<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe74q_b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-5-sharp" /></template>
<style>
.fe74q_b7g {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm13-2h4.5V8H14zm7.5-1.5v-5H23v5z");
}

</style>
