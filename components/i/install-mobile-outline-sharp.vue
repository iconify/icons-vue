<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_azdqb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:install-mobile-outline-sharp" /></template>
<style>
.o_azdqb-b {
  fill: currentColor;
  d: path("M6 22V2h8.077v1H7v1.5h7.077v1H7v13h10v-2h1V22zm1-2.5V21h10v-1.5zm11-6.212l-4.308-4.307l.708-.708l3.1 3.1V3.5h1v7.873l3.1-3.1l.708.708zM7 4.5V3zm0 15V21z");
}

</style>
