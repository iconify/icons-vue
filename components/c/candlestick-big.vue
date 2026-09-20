<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w48k0s7hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w48k0s7hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:candlestick-big" /></template>
