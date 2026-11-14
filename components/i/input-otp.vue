<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b16xpdbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:input-otp" /></template>
<style>
.b16xpdbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8H7v8H2.5Zm7.25 0h4.5v8h-4.5ZM17 8h4.5v8H17ZM4.75 12h.01M12 12h.01m7.24 0h.01");
}

</style>
