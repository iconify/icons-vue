<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5-wb9brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5-wb9brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ferris-wheel-line" /></template>
