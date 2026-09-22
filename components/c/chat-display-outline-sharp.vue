<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0uzszbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-display-outline-sharp" /></template>
<style>
.h0uzszbqu {
  fill: currentColor;
  d: path("M4 12.5v5.144V4zm2.5-2h11v-1h-11zm0-3h11v-1h-11zM3 20.077V3h18v9.5h-1V4H4v13.644L5.65 16h4.292v1H6.077zM6.5 13.5h3.442v-1H6.5zm5.827 7.5v-6.115H21V21zm1-1H20v-4.115h-6.673z");
}

</style>
