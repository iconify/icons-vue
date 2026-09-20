<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vym98jbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vym98jbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-first-quarter-moon-night-moon-first-half-quarter-time-weather" /></template>
