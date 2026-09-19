<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuor6xgkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuor6xgkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-037" /></template>
