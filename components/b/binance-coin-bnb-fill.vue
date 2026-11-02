<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpm12ebsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpm12ebsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binance-coin-bnb-fill" /></template>
