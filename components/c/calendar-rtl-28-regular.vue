<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="czzk5bt7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-28-regular" /></template>
<style>
.czzk5bt7n {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v15.5A3.25 3.25 0 0 0 6.25 25h15.5A3.25 3.25 0 0 0 25 21.75V6.25A3.25 3.25 0 0 0 21.75 3zM4.5 9.503h19V21.75a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75zm14.751 7.998a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m-5.254 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m5.254-5a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m-5.254 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m-5.255 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M6.25 4.5h15.5c.966 0 1.75.784 1.75 1.75v1.753h-19V6.25c0-.966.784-1.75 1.75-1.75");
}

</style>
