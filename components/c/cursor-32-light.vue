<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ecl79bp1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-32-light" /></template>
<style>
.ecl79bp1q {
  fill: currentColor;
  d: path("M5.999 3.503c0-1.253 1.445-1.954 2.429-1.178L27.424 17.32c1.117.881.494 2.677-.93 2.677H16.303a.5.5 0 0 0-.393.192L8.677 29.42c-.88 1.123-2.681.5-2.68-.925zm1.81-.393a.5.5 0 0 0-.81.393l-.003 24.993a.5.5 0 0 0 .894.309l7.232-9.233a1.5 1.5 0 0 1 1.18-.575h10.193a.5.5 0 0 0 .31-.893z");
}

</style>
