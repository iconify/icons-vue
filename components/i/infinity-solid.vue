<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx_5-drdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx_5-drdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:infinity-solid" /></template>
