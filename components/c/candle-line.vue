<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe88tlfgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe88tlfgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candle-line" /></template>
