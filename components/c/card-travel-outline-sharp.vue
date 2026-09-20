<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0lxu0bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:card-travel-outline-sharp" /></template>
<style>
.p0lxu0bjm {
  fill: currentColor;
  d: path("M4 19h16v-2.423H4zm-1 1V7h5V3.77h8V7h5v13zm1-5.577h16V8h-4v1.616h-1V8H9v1.616H8V8H4zM9 7h6V4.77H9zM4 19V8v1.616V8v1.616V8z");
}

</style>
