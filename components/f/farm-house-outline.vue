<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfw4fsb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfw4fsb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:farm-house-outline" /></template>
