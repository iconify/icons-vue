<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgno_hn4s.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tgno_hn4s"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-candlestick" /></template>
