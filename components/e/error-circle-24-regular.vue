<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbaq1nb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-24-regular" /></template>
<style>
.tbaq1nb6h {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2m0 1.5a8.5 8.5 0 1 0 0 17a8.5 8.5 0 0 0 0-17m-.001 11.002a.999.999 0 1 1-.001 1.997a.999.999 0 0 1 .001-1.997M11.994 7a.75.75 0 0 1 .744.647l.007.102l.004 4.502a.75.75 0 0 1-1.493.103l-.007-.102l-.004-4.501a.75.75 0 0 1 .75-.751");
}

</style>
