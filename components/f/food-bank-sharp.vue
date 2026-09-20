<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8axolb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:food-bank-sharp" /></template>
<style>
.u8axolb6v {
  fill: currentColor;
  d: path("M10.308 17.346h.846v-3.384q.529 0 .899-.37t.37-.9v-2.538h-.846v2.538h-.423v-2.538h-.846v2.538h-.423v-2.538h-.846v2.538q0 .53.37.9t.899.37zm3.384 0h.847v-7.192q-.691 0-1.192.497q-.5.497-.5 1.195v2.539h.845zM5 20V9.5l7-5.27l7 5.27V20z");
}

</style>
