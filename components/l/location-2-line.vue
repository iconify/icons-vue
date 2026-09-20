<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysq25cbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysq25cbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-2-line" /></template>
