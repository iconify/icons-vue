<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6b6h-biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6b6h-biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-20-percent" /></template>
