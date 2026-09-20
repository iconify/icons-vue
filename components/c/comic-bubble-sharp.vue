<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh9y_o5gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comic-bubble-sharp" /></template>
<style>
.vh9y_o5gw {
  fill: currentColor;
  d: path("m11 2.523l2.483 2.483h3.51v3.51L19.478 11l-2.708 2.708l2.49 4.861l-.69.69l-4.861-2.49L11 19.477l-2.483-2.483h-3.51v-3.51L2.522 11l2.483-2.483v-3.51h3.51z");
}

</style>
