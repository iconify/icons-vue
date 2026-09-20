<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reir_ycgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-alert-outline-sharp" /></template>
<style>
.reir_ycgi {
  fill: currentColor;
  d: path("M20.288 16.213Q20 15.925 20 15.5t.288-.712T21 14.5t.713.288t.287.712t-.288.713T21 16.5t-.712-.288M20 13V7h2v6zM1 18V6h17v2H3v8h15q0 .575.213 1.088t.562.912zm3-3V9h14v6z");
}

</style>
