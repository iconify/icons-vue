<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpq1hhjvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpq1hhjvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-distribute-end" /></template>
