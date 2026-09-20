<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ody3_jmli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ody3_jmli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-third-quarter-moon-night-moon-third-half-quarter-time-weather" /></template>
