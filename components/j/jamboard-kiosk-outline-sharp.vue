<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jujkj_ygm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:jamboard-kiosk-outline-sharp" /></template>
<style>
.jujkj_ygm {
  fill: currentColor;
  d: path("M7 20v-1h4.5v-3H3V4h18v12h-8.5v3H17v1zm-3-5h16V5H4zm0 0V5z");
}

</style>
