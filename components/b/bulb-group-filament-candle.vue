<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk6r-mbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk6r-mbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-filament-candle" /></template>
