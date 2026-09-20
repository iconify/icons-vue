<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0sl8tbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0sl8tbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:credit-card-multiple" /></template>
