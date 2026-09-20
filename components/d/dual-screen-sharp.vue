<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jizizubxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dual-screen-sharp" /></template>
<style>
.jizizubxe {
  fill: currentColor;
  d: path("M5 18.277V3l8 3.198v15.29zM15 18V4.842L10.392 3H19v15z");
}

</style>
