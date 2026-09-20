<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztt7er2qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-alert-sharp" /></template>
<style>
.ztt7er2qa {
  fill: currentColor;
  d: path("M1 18V6h17v10q0 .575.213 1.088t.562.912zm19-5V7h2v6zm.288 3.213Q20 15.924 20 15.5t.288-.712T21 14.5t.713.288t.287.712t-.288.713T21 16.5t-.712-.288");
}

</style>
