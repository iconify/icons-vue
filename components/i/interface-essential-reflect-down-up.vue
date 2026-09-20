<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiekhvbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fiekhvbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-reflect-down-up" /></template>
