<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcvgcht7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcvgcht7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electrical-resistance" /></template>
