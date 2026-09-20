<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm7nbsb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-mac-outline-sharp" /></template>
<style>
.xm7nbsb6o {
  fill: currentColor;
  d: path("M1 19.27V18h2.77L3 17.23V4h18v13.23l-.77.77H23v1.27zm11.434-.683q.182-.181.182-.433t-.182-.434t-.434-.18t-.434.181t-.182.434q0 .252.182.433t.434.182t.434-.181M4 17h16V5H4zm0 0V5z");
}

</style>
