<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf1vesb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf1vesb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-m" /></template>
