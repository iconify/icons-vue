<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-lstsb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-stand" /></template>
<style>
.e-lstsb-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75h7q1 0 1.41.91l1.68 3.68q.41.91-.59.91H6q-1 0-.59-.91l1.68-3.68q.41-.91 1.41-.91m0 8.5l-1 1.5m8-1.5l1 1.5M12 8.25v13m0-5.75l-5.5 5.75M12 15.5l5.5 5.75");
}

</style>
