<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo276fipa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo276fipa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-3-line" /></template>
