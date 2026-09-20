<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igv29e4iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":60};
const content = `<path class="igv29e4iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alpha-vantage" /></template>
