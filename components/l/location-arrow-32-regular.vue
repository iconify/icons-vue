<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oqxr3bbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-32-regular" /></template>
<style>
.oqxr3bbwg {
  fill: currentColor;
  d: path("M28.863 5.722c.622-1.617-.967-3.206-2.584-2.584l-21.995 8.46c-1.812.696-1.668 3.306.21 3.8l9.022 2.375a1 1 0 0 1 .713.712l2.374 9.023c.494 1.877 3.104 2.02 3.8.209zm-1.866-.717l-8.46 21.994l-2.374-9.023a3 3 0 0 0-2.138-2.138l-9.023-2.374z");
}

</style>
