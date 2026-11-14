<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li96v1bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:device-group" /></template>
<style>
.li96v1bko {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h2.75q3.375 0 3.375 3.375v2.75q0 3.375-3.375 3.375h-2.75q-3.375 0-3.375-3.375v-2.75q0-3.375 3.375-3.375m13.75 0h-2.75q-3.375 0-3.375 3.375v2.75q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375v-2.75q0-3.375-3.375-3.375m-8.25 11h2.75q3.375 0 3.375 3.375v2.75q0 3.375-3.375 3.375h-2.75q-3.375 0-3.375-3.375v-2.75q0-3.375 3.375-3.375");
}

</style>
