<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz1m-7h_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1m-7h_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binance-coin-bnb-line" /></template>
