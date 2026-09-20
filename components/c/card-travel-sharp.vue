<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jggx_ob-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:card-travel-sharp" /></template>
<style>
.jggx_ob-x {
  fill: currentColor;
  d: path("M3 20V7h5V3.77h8V7h5v13zM9 7h6V4.77H9zm-5 9.577h16v-2.154H4z");
}

</style>
