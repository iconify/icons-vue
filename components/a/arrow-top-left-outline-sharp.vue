<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krb_--bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-top-left-outline-sharp" /></template>
<style>
.krb_--bfb {
  fill: currentColor;
  d: path("M17 20V10H7.825l3.6 3.6l-1.4 1.425L4 9l6-6l1.425 1.425L7.825 8H19v12z");
}

</style>
