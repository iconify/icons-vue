<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plcluylce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gamma" /></template>
<style>
.plcluylce {
  fill: var(--svg-color--fe0024, #fe0024);
  d: path("M12.563 10.543L20.123 3l.787.788l-7.577 7.666L21 11.437v1.126h-7.667l5.417 5.383l-.788.787l-5.394-5.512v7.222h-1.125v-7.217L3.782 21L3 20.212l7.667-7.65H3v-1.125l7.667.017l-5.136-5.22l.788-.787l5.118 5.096V3h1.126z");
}

</style>
