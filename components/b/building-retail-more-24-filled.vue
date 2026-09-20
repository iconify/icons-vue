<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elc6oue9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-retail-more-24-filled" /></template>
<style>
.elc6oue9q {
  fill: currentColor;
  d: path("M6.22 3a1.75 1.75 0 0 0-1.347.633l-3.58 4.32C.616 8.766 1.195 10 2.253 10h19.492c1.059 0 1.638-1.233.963-2.048l-3.581-4.319A1.75 1.75 0 0 0 17.78 3zM3 11.5v7.25a2.5 2.5 0 0 0 2.5 2.5h13a2.5 2.5 0 0 0 2.5-2.5V11.5zm6 3.75a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m3 1.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m5.5-1.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

</style>
