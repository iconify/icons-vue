<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7u7kc2ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-info-rounded" /></template>
<style>
.p7u7kc2ij {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v2.348q0 .344-.304.49q-.304.148-.592-.029q-.685-.373-1.464-.572q-.779-.2-1.607-.2q-2.67 0-4.534 1.865t-1.865 4.534q0 .277.012.56t.079.555q.067.322-.121.577q-.188.256-.51.256zm9.549.836Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21t-2.835-1.164m3.108-.409q.112-.111.112-.273v-2.308q0-.162-.112-.273T17 16.462t-.273.111t-.111.273v2.308q0 .162.111.273t.273.112t.273-.112m.077-4.115q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
