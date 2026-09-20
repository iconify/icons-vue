<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rck38obnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rck38obnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camer-fill" /></template>
