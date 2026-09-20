<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2kojzbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:account-balance-outline" /></template>
<style>
.h2kojzbjv {
  fill: currentColor;
  d: path("M5 17v-7h2v7zm6 0v-7h2v7zm-9 4v-2h20v2zm15-4v-7h2v7zM2 8V6l10-5l10 5v2zm4.45-2h11.1zm0 0h11.1L12 3.25z");
}

</style>
