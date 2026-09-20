<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvisqsbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-0-sharp" /></template>
<style>
.pvisqsbvw {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm2-2h15.5V8H3zm18.5-1.5v-5H23v5zM3 16V8h15.5v8z");
}

</style>
