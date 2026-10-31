<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7whn1bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7whn1bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-bitcoin-duotone-round" /></template>
