<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxz4xdoel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qxz4xdoel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-moon-astronomy-moon-science-space-crescent" /></template>
