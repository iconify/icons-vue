<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5vavnc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-fill-round" /></template>
<style>
.d5vavnc8a {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-1.903-1.902c-.452.13-.92.196-1.39.195H7a5 5 0 0 1-5-5v-5c0-1.724.884-3.326 2.346-4.239L1.293 3.707a.999.999 0 1 1 1.414-1.414m18.768 15.94L7.914 4.672l.379-.379C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293l1.725 1.725A5 5 0 0 1 22 11v5a5 5 0 0 1-.525 2.233m-7.443-1.787l-1.514-1.513a2 2 0 0 1-1.931-.518a2 2 0 0 1-.52-1.933l-1.513-1.514a4.002 4.002 0 0 0 5.478 5.478");
}

</style>
