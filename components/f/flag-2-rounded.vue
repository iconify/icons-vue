<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgtgj83hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-2-rounded" /></template>
<style>
.jgtgj83hx {
  fill: currentColor;
  d: path("M7 12.539V20.5q0 .213-.144.356T6.499 21t-.356-.144T6 20.5V4.808q0-.343.232-.576T6.808 4h11.89q.218 0 .4.103t.289.267t.126.373t-.087.423l-1.522 3.103l1.522 3.103q.105.214.087.423t-.126.373t-.29.268q-.182.102-.399.102z");
}

</style>
