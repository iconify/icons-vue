<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lenh45b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lenh45b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-cloud-1-cloud-meteorology-cloudy-overcast-cover-weather" /></template>
