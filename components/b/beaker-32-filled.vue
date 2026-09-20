<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ep-a0ykor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:beaker-32-filled" /></template>
<style>
.ep-a0ykor {
  fill: currentColor;
  d: path("M12 5v8.438a4 4 0 0 1-.712 2.277L9.706 18h12.587l-1.582-2.285A4 4 0 0 1 20 13.438V5h1a1 1 0 1 0 0-2H11a1 1 0 1 0 0 2zm11.677 15H8.322l-2.744 3.963C4.104 26.092 5.628 29 8.218 29h15.564c2.589 0 4.113-2.908 2.639-5.037z");
}

</style>
