<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuyuwub9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gallery-thumbnail-outline-sharp" /></template>
<style>
.wuyuwub9k {
  fill: currentColor;
  d: path("M2.5 18V6h12v12zm14-7V6h5v5zm1-1h3V7h-3zm-14 7h10V7h-10zm1.192-2.096h7.616l-2.433-3.25L8 14.154l-1.375-1.825zM16.5 18v-5h5v5zm1-1h3v-3h-3zm-14 0V7zm14-7V7zm0 7v-3z");
}

</style>
