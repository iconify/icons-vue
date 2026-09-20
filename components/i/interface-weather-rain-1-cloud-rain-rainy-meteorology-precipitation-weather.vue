<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm9um7bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tm9um7bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-rain-1-cloud-rain-rainy-meteorology-precipitation-weather" /></template>
