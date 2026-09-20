<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkrj1mbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:change-history-outline-sharp" /></template>
<style>
.bkrj1mbdq {
  fill: currentColor;
  d: path("M3.808 19L12 5.885L20.192 19zM5.6 18h12.8L12 7.75zm6.4-5.125");
}

</style>
