<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehl-jxdfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehl-jxdfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:camera-lock" /></template>
