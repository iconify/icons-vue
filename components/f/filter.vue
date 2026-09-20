<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdm2rjbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdm2rjbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:filter" /></template>
