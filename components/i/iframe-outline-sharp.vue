<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxttr686s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:iframe-outline-sharp" /></template>
<style>
.oxttr686s {
  fill: currentColor;
  d: path("M11.192 13.808h5.616v-2.616h-5.616zm-.884.884v-4.384h7.384v4.384zM3 19V5h18v14zm1-1h16V8H4z");
}

</style>
