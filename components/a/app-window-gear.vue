<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjh0zxifh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjh0zxifh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:app-window-gear" /></template>
