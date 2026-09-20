<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv-s6pbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glass-cup-outline-sharp" /></template>
<style>
.sv-s6pbil {
  fill: currentColor;
  d: path("M6.027 21L4 3h16l-2.008 18zm.614-3.5l.282 2.5h10.173l.283-2.5zm-.104-1h10.952L18.866 4H5.116zM6.64 20h10.738z");
}

</style>
