<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj431tx8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-4-outline-sharp" /></template>
<style>
.jj431tx8l {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm11-2h6.5V8H12zm9.5-1.5v-5H23v5z");
}

</style>
