<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxyc8_-xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxyc8_-xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-g" /></template>
