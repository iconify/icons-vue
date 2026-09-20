<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdz93i2eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdz93i2eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-30-bluetooth" /></template>
