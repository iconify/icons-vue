<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je8e1dbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:host-sharp" /></template>
<style>
.je8e1dbna {
  fill: currentColor;
  d: path("M3 20V4h7.808v16zm10.192 0V4H21v16zm-7.807-5.615h3v-1h-3zm10.23 0h3v-1h-3zm-10.23-2.808h3v-1h-3zm10.23 0h3v-1h-3zM5.386 8.75h3v-1h-3zm10.23 0h3v-1h-3z");
}

</style>
