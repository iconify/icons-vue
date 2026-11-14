<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuhhn-5yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:editor-theme" /></template>
<style>
.uuhhn-5yf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q4.219 0 7.181 2.315Q22.25 6.465 22.25 10q0 2.186-1.532 3.718T17 15.25h-2q-1.25 0-1.25 1q0 .409.377 1.114q.623 1.164.623 2.136q0 2.75-2.75 2.75q-4.248 0-7.249-3.001T1.75 12t3.001-7.249T12 1.75m2 3q-1.75 0-1.75 1.75T14 8.25t1.75-1.75T14 4.75M7.25 7.5q0 1.75 1.75 1.75t1.75-1.75T9 5.75T7.25 7.5m8.5 2q0 1.75 1.75 1.75t1.75-1.75t-1.75-1.75t-1.75 1.75m-8.25.75q-1.75 0-1.75 1.75t1.75 1.75T9.25 12T7.5 10.25");
}

</style>
