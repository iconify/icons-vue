<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzaol7b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-all-outline-rounded" /></template>
<style>
.qzaol7b1i {
  fill: currentColor;
  d: path("M4 18.385V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475H5.615q-.666 0-1.14-.475T4 18.386m8.5-5.885V19H19v-6.5zm0-1H19V5h-6.5zm-1 0V5H5v6.5zm0 1H5V19h6.5z");
}

</style>
