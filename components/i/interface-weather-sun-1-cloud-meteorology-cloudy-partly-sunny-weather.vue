<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns6fbwp0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ns6fbwp0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-sun-1-cloud-meteorology-cloudy-partly-sunny-weather" /></template>
