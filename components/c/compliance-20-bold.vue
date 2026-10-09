<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwehzwmcr.css';
import '../../css/i/idt7ziwvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwehzwmcr"/><path class="idt7ziwvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compliance-20-bold" /></template>
