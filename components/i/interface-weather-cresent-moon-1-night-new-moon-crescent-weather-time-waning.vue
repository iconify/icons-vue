<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-6ugubog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p-6ugubog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-cresent-moon-1-night-new-moon-crescent-weather-time-waning" /></template>
