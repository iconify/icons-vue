<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il26dnbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il26dnbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-candlestick-fill-round" /></template>
