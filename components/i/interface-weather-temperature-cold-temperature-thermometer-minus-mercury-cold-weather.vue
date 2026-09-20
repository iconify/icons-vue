<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzqiss7xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kzqiss7xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-temperature-cold-temperature-thermometer-minus-mercury-cold-weather" /></template>
