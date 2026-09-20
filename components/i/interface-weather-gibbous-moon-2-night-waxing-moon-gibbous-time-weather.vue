<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khluvqi-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="khluvqi-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-gibbous-moon-2-night-waxing-moon-gibbous-time-weather" /></template>
