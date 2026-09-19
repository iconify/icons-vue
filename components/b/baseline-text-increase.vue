<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lznpx07_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-text-increase" /></template>
<style>
.lznpx07_z {
  fill: currentColor;
  d: path("M.99 19h2.42l1.27-3.58h5.65L11.59 19h2.42L8.75 5h-2.5zm4.42-5.61L7.44 7.6h.12l2.03 5.79zM20 11h3v2h-3v3h-2v-3h-3v-2h3V8h2z");
}

</style>
