<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tppgxbcnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flip-to-front" /></template>
<style>
.tppgxbcnh {
  fill: currentColor;
  d: path("M9.308 16.308q-.69 0-1.153-.463t-.463-1.153V5.616q0-.691.463-1.153T9.308 4h9.077q.69 0 1.153.463T20 5.616v9.076q0 .69-.462 1.153t-1.153.463zm0-1h9.077q.23 0 .423-.193q.192-.192.192-.423V5.616q0-.231-.192-.424T18.384 5H9.308q-.231 0-.423.192q-.193.192-.193.423v9.077q0 .231.193.424q.192.192.423.192M5.23 18.769V20q-.517 0-.874-.357T4 18.77zM4 16.308v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zM7.692 20v-1.23h1.231V20zm3.693 0v-1.23h1.23V20zm3.692 0v-1.23h1.23V20z");
}

</style>
