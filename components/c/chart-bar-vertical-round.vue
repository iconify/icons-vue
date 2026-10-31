<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqrqvz3rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqrqvz3rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-vertical-round" /></template>
