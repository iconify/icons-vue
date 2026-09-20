<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk8u-1b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk8u-1b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-candlestick" /></template>
