<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voata-00v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:listening-session" /></template>
<style>
.voata-00v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 3.25H20q2.25 0 2.25 2.25V9q0 2.25-2.25 2.25h-.71l-2.535 2.305q-.111.1-.251.151t-.29.043q-.149-.007-.284-.071t-.235-.173q-.094-.104-.145-.235q-.05-.13-.05-.27V5.5q0-2.25 2.25-2.25M3.5 10.5v1.298q-1.75.288-1.75 2.327v3.75q0 2.375 2.375 2.375T6.5 17.875v-3.75q0-1.887-1.5-2.275V10.5q0-3 3-3t3 3v1.35q-1.5.388-1.5 2.275v3.75q0 2.375 2.375 2.375t2.375-2.375v-3.75q0-2.039-1.75-2.327V10.5q0-1.864-1.318-3.182T8 6T4.818 7.318T3.5 10.5");
}

</style>
