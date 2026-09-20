<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coz08f0-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coz08f0-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binance-coin-bnb-fill" /></template>
