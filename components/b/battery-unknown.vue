<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-x6zrhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-unknown" /></template>
<style>
.fw-x6zrhb {
  fill: currentColor;
  d: path("M16.477 19.22q0-.292.022-.572t.166-.541q.204-.368.532-.621t.56-.59q.064-.084.164-.49q0-.363-.282-.598T17 15.573q-.367 0-.625.237q-.258.236-.383.604l-.927-.398q.21-.637.737-1.019q.525-.381 1.198-.381q.778 0 1.356.506t.578 1.267q0 .217-.055.426q-.056.208-.186.383q-.237.348-.545.603t-.51.622q-.134.237-.134.796zm.017 1.96q-.21-.204-.21-.505q0-.287.21-.492t.504-.204t.503.206t.209.494t-.209.497t-.503.209t-.504-.205M8.692 21q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v6.903q-2.135.275-3.587 1.897t-1.452 3.853q0 .843.227 1.618t.663 1.44z");
}

</style>
