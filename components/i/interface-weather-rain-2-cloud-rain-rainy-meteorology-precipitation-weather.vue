<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1nckkbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c1nckkbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-rain-2-cloud-rain-rainy-meteorology-precipitation-weather" /></template>
