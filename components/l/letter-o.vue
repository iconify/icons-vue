<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik1ry9vnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik1ry9vnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-o" /></template>
