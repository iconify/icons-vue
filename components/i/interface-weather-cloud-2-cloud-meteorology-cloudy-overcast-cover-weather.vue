<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caseumbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="caseumbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-cloud-2-cloud-meteorology-cloudy-overcast-cover-weather" /></template>
