<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x3fj0_s_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-28-filled" /></template>
<style>
.x3fj0_s_g {
  fill: currentColor;
  d: path("M3 9.5v12.25A3.25 3.25 0 0 0 6.25 25h15.5A3.25 3.25 0 0 0 25 21.75V9.5zm16.259 8.001a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-5.255 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m5.255-5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-5.255 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-5.254 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M6.25 3A3.25 3.25 0 0 0 3 6.25V8h22V6.25A3.25 3.25 0 0 0 21.75 3z");
}

</style>
