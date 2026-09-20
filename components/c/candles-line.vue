<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzu25db3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzu25db3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candles-line" /></template>
