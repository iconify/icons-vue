<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgi27wbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:install-mobile-sharp" /></template>
<style>
.hgi27wbjh {
  fill: currentColor;
  d: path("M6 22V2h8.077v3.5H7v13h10v-2h1V22zm12-8.711L13.692 8.98l.708-.708l3.1 3.1V3.5h1v7.873l3.1-3.1l.708.708z");
}

</style>
