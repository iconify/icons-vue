<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3t732w4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hardware-sharp" /></template>
<style>
.q3t732w4k {
  fill: currentColor;
  d: path("M9 11V8H4q0-2.075 1.463-3.537T9 3h6v3l3-3h2v8h-2l-3-3v3zm0 10v-8h6v8z");
}

</style>
