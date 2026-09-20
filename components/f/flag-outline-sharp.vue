<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hydbn0byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flag-outline-sharp" /></template>
<style>
.hydbn0byu {
  fill: currentColor;
  d: path("M5 21V4h9l.4 2H20v10h-7l-.4-2H7v7zm9.65-7H18V8h-5.25l-.4-2H7v6h7.25z");
}

</style>
