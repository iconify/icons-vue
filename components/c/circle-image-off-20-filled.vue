<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xb2tjk0hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-off-20-filled" /></template>
<style>
.xb2tjk0hc {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-.268-.267c-.395.262-.87.414-1.379.414h-5c-.51 0-.984-.152-1.379-.414l3.172-3.172a1 1 0 0 1 1.414 0l-1.224-1.224c-.328.088-.64.26-.897.517l-3.172 3.172A2.5 2.5 0 0 1 8 15.5v-5c0-.51.152-.984.414-1.379l-.718-.718A3.5 3.5 0 0 0 7 10.5v3.415a6 6 0 0 1-3.581-9.789L2.146 2.854a.5.5 0 0 1 0-.708M15.5 8a2.5 2.5 0 0 1 2.5 2.5v5q-.001.18-.026.352l-7.826-7.825q.172-.025.352-.027zm-.5 2a1 1 0 1 0 0 2a1 1 0 0 0 0-2M8 2a6 6 0 0 1 5.915 5H10.5c-.413 0-.809.07-1.177.202l-4.37-4.371A5.97 5.97 0 0 1 8 2");
}

</style>
