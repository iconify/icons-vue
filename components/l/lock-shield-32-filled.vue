<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lj336e7su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-32-filled" /></template>
<style>
.lj336e7su {
  fill: currentColor;
  d: path("M23.293 15.766c.376-.354 1.038-.354 1.414 0c.943.887 2.755 2.298 4.982 2.588c.445.057.811.389.811.803v3.87c0 5.204-5.17 7.093-6.288 7.44a.7.7 0 0 1-.423 0c-1.118-.347-6.288-2.236-6.288-7.44l-.001-3.87c0-.414.366-.746.81-.803c2.228-.29 4.04-1.7 4.983-2.588M16 2a6 6 0 0 1 6 6v3.028a4.5 4.5 0 0 1 3.956 3.843l-.22-.198l-.186-.157a2.59 2.59 0 0 0-3.1 0l-.185.157c-.816.767-2.206 1.824-3.822 2.14l-.326.053c-.729.095-1.569.57-1.933 1.393A1.75 1.75 0 1 0 16 21.75l.001 1.277l.004.295c.08 2.509 1.17 4.364 2.47 5.678H10.5A4.5 4.5 0 0 1 6 24.5v-9a4.5 4.5 0 0 1 4-4.472V8a6 6 0 0 1 6-6m0 2a4 4 0 0 0-4 4v3h8V8a4 4 0 0 0-4-4");
}

</style>
