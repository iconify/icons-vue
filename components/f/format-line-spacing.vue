<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irq17xbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="irq17xbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-line-spacing" /></template>
