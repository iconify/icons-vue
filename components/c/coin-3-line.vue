<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7452wbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7452wbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-3-line" /></template>
