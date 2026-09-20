<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8h-_d-zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q8h-_d-zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:horizontal-slider-2-remix" /></template>
