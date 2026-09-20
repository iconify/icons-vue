<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2c-s1u4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2c-s1u4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:candlestick" /></template>
