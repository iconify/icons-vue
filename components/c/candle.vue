<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnsohj1uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnsohj1uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:candle" /></template>
