<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adsqt6b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-6-outline-sharp" /></template>
<style>
.adsqt6b_q {
  fill: currentColor;
  d: path("M4.385 14.616V9.385h11v5.23zM2 17V7h17.885v10zm1-1h15.885V8H3zm17.885-1.884V9.904H22v4.212z");
}

</style>
