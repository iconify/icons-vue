<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xogdn0b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brunch-dining-sharp" /></template>
<style>
.xogdn0b7d {
  fill: currentColor;
  d: path("M3 21v-1h12.462v1zm0-3.384v-1h4.23v-1.154h4v1.154h4.232v1zM18.385 21v-6.215q-.708-.64-1.2-1.535q-.493-.894-.493-2.03V3H21v8.22q0 1.136-.451 2.033t-1.164 1.532V20H21v1zm-.693-12.615H20V4h-2.308z");
}

</style>
