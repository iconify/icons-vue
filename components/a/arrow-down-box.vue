<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcz7dqaye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz7dqaye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-down-box" /></template>
