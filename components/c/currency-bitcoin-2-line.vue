<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2x_3ebpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2x_3ebpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-2-line" /></template>
