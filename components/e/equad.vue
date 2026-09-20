<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olehajbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:equad" /></template>
<style>
.olehajbqc {
  fill: var(--svg-color--191a4c, #191a4c);
  d: path("m16.552 19.76l1.08 1.232h2.813l-6.188-6.75h-2.531l3.313 3.786a6.75 6.75 0 1 1 1.997-1.524l1.496 1.687a9.001 9.001 0 1 0-1.974 1.57z");
}

</style>
