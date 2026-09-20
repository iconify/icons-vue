<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptod-efkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-alt-sharp" /></template>
<style>
.ptod-efkp {
  fill: currentColor;
  d: path("M2 19V5h20v14zm6.654-2.52h6.692v-1.538H8.654zm-3.116-3.25h1.539v-1.538H5.538zm3.789 0h1.538v-1.538H9.327zm3.807 0h1.539v-1.538h-1.539zm3.789 0h1.539v-1.538h-1.539zM5.538 9.98h1.539V8.443H5.538zm3.789 0h1.538V8.443H9.327zm3.807 0h1.539V8.443h-1.539zm3.693.097h1.538V8.539h-1.538z");
}

</style>
