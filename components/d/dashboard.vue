<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd8_36abv.css';
import '../../css/d/de8636buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vd8_36abv"/><path class="de8636buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dashboard" /></template>
