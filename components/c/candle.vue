<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39asb60y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r39asb60y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:candle" /></template>
