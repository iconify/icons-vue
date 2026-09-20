<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucfaugjig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucfaugjig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binance-usd-busd-fill" /></template>
