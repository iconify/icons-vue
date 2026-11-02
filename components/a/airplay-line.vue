<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f92d32byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f92d32byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airplay-line" /></template>
