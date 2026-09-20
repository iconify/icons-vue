<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j00fqrc8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-indent-decrease-outline-sharp" /></template>
<style>
.j00fqrc8k {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm8-3.75v-1h8v1zm0-3.75v-1h8v1zm0-3.75v-1h8v1zM4 5V4h16v1zm2.808 9.808L4 12l2.808-2.808z");
}

</style>
