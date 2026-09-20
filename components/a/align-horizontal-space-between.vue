<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_2ivbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2_2ivbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-space-between" /></template>
