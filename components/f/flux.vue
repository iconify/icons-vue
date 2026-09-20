<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amqf--f2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flux" /></template>
<style>
.amqf--f2u {
  fill: var(--svg-color--2c61d3, #2c61d3);
  fill-rule: evenodd;
  d: path("M19.941 7.5L12.001 3L4.058 7.5v4.154l2.647-1.5l2.647 1.5V10.5L15.441 7l4.5 2.587zm0 9l-4.673 2.649l-4.327-2.524v-5.25l4.5-2.625l4.5 2.625zm-6.208 3.518L12 21l-3.75-2.125l1.76-.997zm-6.94-1.968l2.56-1.493v-3.088l-2.647-1.544l-2.647 1.544v3.03z");
}

</style>
