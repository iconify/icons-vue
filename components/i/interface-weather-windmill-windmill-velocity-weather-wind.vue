<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds5-kubap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ds5-kubap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-windmill-windmill-velocity-weather-wind" /></template>
