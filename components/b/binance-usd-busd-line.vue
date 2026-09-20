<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bceb90b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bceb90b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binance-usd-busd-line" /></template>
