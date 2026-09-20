<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-oo63zif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g-oo63zif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-umbrella-close-storm-rain-umbrella-close-weather" /></template>
