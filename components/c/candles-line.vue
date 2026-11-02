<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqig8abcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqig8abcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candles-line" /></template>
