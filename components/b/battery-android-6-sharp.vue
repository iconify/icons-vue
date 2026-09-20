<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6-07zc8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-6-sharp" /></template>
<style>
.t6-07zc8p {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm15-2h2.5V8H16zm5.5-1.5v-5H23v5z");
}

</style>
