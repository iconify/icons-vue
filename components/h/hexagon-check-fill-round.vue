<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cul32lbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cul32lbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-check-fill-round" /></template>
