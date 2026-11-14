<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3qz0gm7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circle-filled" /></template>
<style>
.w3qz0gm7y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001-4.039 2.855-6.896T12 2.247t6.895 2.857T21.75 12q.001 4.039-2.855 6.896T12 21.753q-4.04 0-6.895-2.857Q2.249 16.039 2.25 12");
}

</style>
