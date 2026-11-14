<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okvmtwb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dvd-disc" /></template>
<style>
.okvmtwb8b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m3.602 1.172q.677 3.838 4.34 5.171q.069.025.142.036q.073.012.147.008q.074-.003.145-.021q.072-.017.139-.048q.067-.032.127-.075q.059-.044.109-.098t.088-.118q.039-.063.064-.133q.051-.14.044-.289t-.069-.284t-.173-.236t-.251-.152q-2.848-1.036-3.374-4.021q-.026-.147-.106-.273q-.081-.126-.203-.211q-.122-.086-.268-.118q-.145-.033-.292-.007q-.073.013-.142.04t-.131.066t-.116.091t-.095.112q-.043.06-.073.128t-.045.14q-.016.072-.018.146t.011.146");
}

</style>
