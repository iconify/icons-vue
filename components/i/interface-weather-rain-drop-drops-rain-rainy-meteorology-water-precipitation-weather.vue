<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eclize6ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="eclize6ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-rain-drop-drops-rain-rainy-meteorology-water-precipitation-weather" /></template>
