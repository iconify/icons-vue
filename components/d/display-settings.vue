<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv36dorme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-settings" /></template>
<style>
.wv36dorme {
  fill: currentColor;
  d: path("M8 14.192h.885v-3H8v1.058H6.5v.885H8zm1.885-1.057H17.5v-.885H9.885zm5.23-2.327H16V9.75h1.5v-.885H16V7.809h-.885zM6.5 9.75h7.616v-.885H6.5zM9 20v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.769q0 .69-.463 1.153T19.385 18H15v2z");
}

</style>
