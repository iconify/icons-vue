<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hodbwfbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hodbwfbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-3x3-fill" /></template>
