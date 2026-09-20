<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rku_ynb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-received-outline" /></template>
<style>
.rku_ynb0t {
  fill: currentColor;
  d: path("M6 18V9h1v7.292L18.292 5l.708.708L7.708 17H15v1z");
}

</style>
