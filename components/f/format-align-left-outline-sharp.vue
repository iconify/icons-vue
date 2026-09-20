<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbuv6xlgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-align-left-outline-sharp" /></template>
<style>
.fbuv6xlgs {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h12v2zm0-4v-2h18v2zm0-4V7h12v2zm0-4V3h18v2z");
}

</style>
