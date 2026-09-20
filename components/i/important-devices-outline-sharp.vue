<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkxqtcb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:important-devices-outline-sharp" /></template>
<style>
.lkxqtcb5h {
  fill: currentColor;
  d: path("M15.692 20v-8.796H21V20zm.77-1.77h3.769v-5.257h-3.77zM8.154 20v-1H10.5v-3H3V4h16v5.204h-1V5H4v10h9.692v1H11.5v3h2.346v1zm.969-6.866L11 11.616l1.877 1.519l-.696-2.389l1.896-1.542h-2.339L11 6.98l-.738 2.223h-2.34l1.896 1.542zM11 10");
}

</style>
