<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv9d3tbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rv9d3tbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-gibbous-moon-1-night-moon-weather-gibbous-time-waning" /></template>
