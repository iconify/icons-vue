<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd1iwracu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compare-outline" /></template>
<style>
.fd1iwracu {
  fill: currentColor;
  d: path("M11 22.23V20H5.616q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4H11V1.77h1v20.46zM5 18h6v-7.192zm9 2v-8l5 6V5.616q0-.231-.192-.424T18.384 5H14V4h4.385q.69 0 1.152.463T20 5.616v12.769q0 .69-.463 1.153T18.385 20z");
}

</style>
