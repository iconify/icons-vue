<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvihosbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-gym" /></template>
<style>
.wvihosbzl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 11.136q1.162 2.259.575 4.929q-.772 3.51-3.992 5.107q-.157.078-.333.078H9q-.176 0-.333-.078q-3.22-1.597-3.992-5.107q-.587-2.67.575-4.929V7q0-3.25 3.25-3.25h7q3.25 0 3.25 3.25zm-12-2.05Q8.864 6.953 12 6.953t5.25 2.133V7q0-1.75-1.75-1.75h-7Q6.75 5.25 6.75 7zm3.982 2.463Q8.016 12.588 8 15.496q-.001.149.056.287q.056.138.161.244t.242.164t.287.059q.074 0 .146-.014q.073-.014.141-.042q.069-.027.13-.068q.062-.041.114-.093t.094-.113t.07-.129t.044-.141t.015-.146q.01-1.881 1.768-2.553q.069-.027.131-.066q.063-.04.117-.09q.053-.051.096-.111t.073-.128t.046-.14q.017-.072.019-.145q.002-.074-.011-.147t-.038-.142q-.027-.069-.066-.131q-.04-.063-.09-.117q-.051-.053-.111-.096t-.128-.073t-.14-.046q-.072-.017-.145-.019q-.074-.002-.147.011t-.142.038");
}

</style>
