<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw9doviwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-landscape-add-sharp" /></template>
<style>
.sw9doviwb {
  fill: currentColor;
  d: path("M3 19V5h18v7.986q-.554-.298-1.182-.45q-.628-.151-1.318-.151q-.237 0-.453.012t-.432.063V8.384H9v.885h7.73v3.416q-.54.18-1.008.456t-.876.634v-2.621H6.385v4.462h7.119q-.252.513-.378 1.083T13 17.89q0 .295.03.57q.031.273.103.54zm15 2v-2.616h-2.615v-1H18V14.77h1v2.615h2.616v1H19V21z");
}

</style>
