<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0ucb-12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-outline" /></template>
<style>
.o0ucb-12u {
  fill: currentColor;
  d: path("M15.192 19v-5.808H21V19zm-4-8.192V5H21v5.808zM3 19v-5.808h9.808V19zm0-8.192V5h5.808v5.808zm9.192-1H20V6h-7.808zM4 18h7.808v-3.808H4zm12.192 0H20v-3.808h-3.808zM4 9.808h3.808V6H4zm3.808 0");
}

</style>
