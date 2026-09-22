<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxqedq0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eyebrow-sharp" /></template>
<style>
.vsxqedq0x {
  fill: currentColor;
  d: path("M14.923 13.558q-.967 0-1.947.131t-2.312.475t-3.191.934t-4.598 1.533l-1.086-.752V9.642q3.257-.578 6.549-1.11T14.941 8q2.966 0 4.88 1.949q1.915 1.949 2.376 5.436l-.948.386q-1.523-1-3.294-1.606t-3.033-.607");
}

</style>
