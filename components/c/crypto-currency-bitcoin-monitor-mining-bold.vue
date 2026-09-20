<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsf19acra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsf19acra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:crypto-currency-bitcoin-monitor-mining-bold" /></template>
