<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vffgkyb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vffgkyb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calibrate" /></template>
