<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wcoe8h-bj"/><path class="ivyij9rll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitwarden-authenticator" /></template>
<style>
.ivyij9rll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.397 38.362c.379.184.827.184 1.206 0c6.087-2.964 10.63-7.542 10.63-12.222V12.882c0-.763-.62-1.382-1.383-1.382h-19.7c-.763 0-1.382.619-1.382 1.382V26.14c0 4.68 4.542 9.258 10.63 12.222ZM16 5.5H9.5a4 4 0 0 0-4 4V16m37 0V9.5a4 4 0 0 0-4-4H32M5.5 32v6.5a4 4 0 0 0 4 4H16m16 0h6.5a4 4 0 0 0 4-4V32");
}

.wcoe8h-bj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 34.798c4.715-2.505 7.788-5.876 7.788-8.658V14.956h-7.776z");
}

</style>
