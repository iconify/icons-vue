<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqrzrq8mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:corporate-fare-outline-sharp" /></template>
<style>
.jqrzrq8mn {
  fill: currentColor;
  d: path("M2.73 20.154v-17h9v4h9.54v13zm1-1h7v-3h-7zm0-4h7v-3h-7zm0-4h7v-3h-7zm0-4h7v-3h-7zm8 12h8.54v-11h-8.54zm2.386-7v-1H17.5v1zm0 4v-1H17.5v1z");
}

</style>
